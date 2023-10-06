pipeline {
    agent { 
        node { label "maven" }
    }
    stages {
        stage("Tests") {
            steps {
                sh "./mvnw verify"
            }
        }
    }
}