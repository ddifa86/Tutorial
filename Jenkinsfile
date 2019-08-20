pipeline {
    agent any

    stages {
        stage('Init')
        {
            steps{
                echo "GIT_COMMIT is ${env.GIT_COMMIT}"
            }            
        }
        stage('Build') {
            steps {
                echo 'Building..'
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
