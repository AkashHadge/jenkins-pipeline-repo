pipeline {
    agent any

    stages {
        stage('compile') {
            steps {
                echo 'Compile source code...'
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
