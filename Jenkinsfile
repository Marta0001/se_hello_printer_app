pipeline {
    agent any
    stages {
        stage('deps') {
            steps {
	                 sh 'make deps'
              }
       }
	     stage('Test') {
              step {
                    sh 'make test'
                }
        }
    }
}
