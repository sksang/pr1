pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'First TestPipeLine'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
                echo "In tests currently"
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
        stage('Deploy') {
            steps {
            sh 'python test_file.py'
            }
        }
        
    }
}
