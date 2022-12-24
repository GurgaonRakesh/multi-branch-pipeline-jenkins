
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo 'BhRANCH_NAME is using env'  env.BhRANCH_NAME
                echo 'CHANGE_BRANCH is using env' env.CHANGE_BRANCH 
                echo 'CHANGE_TARGET is using env' env.CHANGE_TARGET
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
