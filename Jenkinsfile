pipeline {
    agent any

    stages {
        stage('git stage') {
            steps {
                git 'https://github.com/puneetgavri/hello-world.git'
            }
        }
		stage('maven stage') {
            steps {
                echo 'Hello maven stage'
            }
        }
		stage('nexus stage') {
            steps {
                echo 'Hello nexus stage'
            }
        }
		stage('sonar stage') {
            steps {
                echo 'Hello sonar stage'
            }
        }
    }
}
