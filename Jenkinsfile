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
                sh 'docker run -d -p 3000:80 tutum/hello-world'
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