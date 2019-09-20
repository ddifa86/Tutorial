pipeline {
    agent any

    stages {
        stage('Init')
        {
            steps{
                echo "GIT_COMMIT is ${env.GIT_COMMIT}"
                echo "GIT_COMMIT is ${env.GIT_BRANCH}"
            }            
        }
        stage('Build') {
            steps {
                echo 'Building..'
                build job: 'MozartBuild', parameters: [string(name: 'SelectProject', value: 'All')]
                echo 'Complete..'
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
