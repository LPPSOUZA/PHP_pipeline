pipeline {
    agent any
    stages {
        stage('Sequencial') {
		   
            stages {
                stage('Sequencial 1') {
                    steps {
                    	bat "php --version"
			bat  "cd Documents\projeto_php"
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
