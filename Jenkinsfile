pipeline {
    agent any

    stages {
		stage('Executing Batch File') {
            steps {
                echo 'Executing Batch File'
				bat 'run.bat'
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