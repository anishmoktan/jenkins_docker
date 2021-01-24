pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hi'
            }
        }
        stage('Building Docker Container') {
            steps {
                sh 'docker --version'
                echo 'Container running on port 3000'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deployed!'
            }
        }
        
    }
}
