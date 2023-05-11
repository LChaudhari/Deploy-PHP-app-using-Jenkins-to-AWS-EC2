pipeline {
    agent any

    stages {
        stage('Deploy') {
            steps {
                sh '''
                sudo -S apt update -y
                cd Deploy-PHP-app-using-Jenkins-to-AWS-EC2
                composer install
                composer install
                php index.php
                php -S localhost:8000
                '''
            }
        }
    }
}