pipeline {
    agent any

    stages {
        stage('Compile') {
            steps {
                echo 'compile source code...checking webhook3'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing source code...'
            }
        }
        stage('Package') {
            steps {
                echo 'Creating package...'
            }
        }
	stage('Deploy') {
		steps {
			echo 'Deploying the package...'
		}
	}
    }
}
