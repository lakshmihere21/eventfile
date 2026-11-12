
pipeline {
    agent any

    stages {

        stage('Checkout') {
            steps {
                echo 'Getting source code'
            }
        }

        stage('Build') {
            steps {
                echo 'Building Event Registration Form'
                bat 'dir'
            }
        }

        stage('Test') {
            steps {
                echo 'Testing Registration Form'
                bat 'findstr /C:"Event Registration Form" index.html'
            }
        }

        stage('Deploy') {
            steps {
                echo 'Project is ready'
            }
        }
    }
}
