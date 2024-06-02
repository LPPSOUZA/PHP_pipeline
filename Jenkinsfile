pipeline {
    agent any
    stages {
        stage('Sequencial') {
		   
            stages {
                stage('Sequencial 1') {
                    steps {
                      sh   "php --version"
                    }
                }
                stage('Secuencial 2') {
                    steps {
                        sh "php hello.php"
                    }
                }
            }
        }
    }
}
