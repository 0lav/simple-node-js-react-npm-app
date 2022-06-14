pipeline {
    agent {
	    label 'h3hexvm'
    }
    stages {
        stage('Build') {
            steps {
                sh 'docker run -p 3000:3000'
            }
        }
    }
}