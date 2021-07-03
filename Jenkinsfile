pipeline {
    agent any

    stages {
		stage('Executing Batch File') {
            steps {
                echo 'Testing..tttt'
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