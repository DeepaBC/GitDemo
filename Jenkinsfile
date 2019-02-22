pipeline {
    agent any

    stages {
        stage('Deploy - Dev') {
            steps {
                echo 'DeployDev'
            }
        }
        stage('Deploy - QA') {
            steps {
                echo 'QA'
                input 'Does the staging environment look ok?"
            }
        }
        stage('Deploy - Production') {
            steps {
                echo 'production'
            }
        }
    }
}
