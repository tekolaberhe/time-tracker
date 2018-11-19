
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                git commit -m "Jenkinsfile"
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
