pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Build successful'
            }
        }

        stage('Deploy') {
            steps {
                sh 'cp index.html /var/www/html/index.html'
            }
        }
    }
}
