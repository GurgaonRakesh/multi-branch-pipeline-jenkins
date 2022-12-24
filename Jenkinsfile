
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                echo  env.BRANCH_NAME
                echo  env.CHANGE_BRANCH 
                echo  env.CHANGE_TARGET
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
