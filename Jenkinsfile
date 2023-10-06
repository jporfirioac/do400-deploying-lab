pipeline {
    agent { 
        node { label "maven" }
    }
    stages {
        stage("Tests") {
            step {
                sh "./mvnw verify"
            }
        }
    }
}