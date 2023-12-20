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
                sh 'python test_file.py'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
