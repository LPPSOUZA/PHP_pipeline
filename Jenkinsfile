pipeline {
    agent any
    stages {
        stage('Sequencial') {
		   
            stages {
                stage('Sequencial 1') {
                    steps {
                      'php --version'
                    }
                }
                stage('Secuencial 2') {
                    steps {
                         'php hello.php'
                    }
                }
            }
        }
    }
}
