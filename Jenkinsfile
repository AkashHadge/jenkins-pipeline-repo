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
                echo 'testing source code...'
            }
        }
        stage('Package') {
            steps {
                echo 'creating package...'
            }
        }
	stage('Deploy') {
		steps {
			echo 'deploying the package...'
		}
	}
    }
}
