pipeline {
    agent any

    stages {
        stage('Clone Repository') {
            steps {
                git 'https://github.com/syedifteqar1/ci-cd-demo.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Build successful'
            }
        }

        stage('Deploy to Apache') {
            steps {
                sh '''
                sudo cp index.html /var/www/html/index.html
                '''
            }
        }
    }
}
