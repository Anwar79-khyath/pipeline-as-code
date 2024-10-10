echo pipeline {^
    agent any^
    stages {^
        stage('Build') {^
            steps {^
                echo 'Building the project...'^
            }^
        }^
        stage('Test') {^
            steps {^
                echo 'Running tests...'^
            }^
        }^
        stage('Deploy') {^
            steps {^
                echo 'Deploying the application...'^
            }^
        }^
    }^
    post {^
        success {^
            echo 'Pipeline finished successfully!'^
        }^
        failure {^
            echo 'Pipeline failed!'^
        }^
    }^
} > Jenkinsfile
