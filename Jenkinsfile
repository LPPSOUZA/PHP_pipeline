pipeline {
    agent any
	environment {
     	
 	}
    stages {
        stage('Sequencial') {
		   
            stages {
                stage('Sequencial 1') {
                    steps {
                    bat "php --version"
                    }
                }
                stage('Secuencial 2') {
                    steps {
                     bat "php hello.php"
                    }
                }
            }
        }
    }
}
