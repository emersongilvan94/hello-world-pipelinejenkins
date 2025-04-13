pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                echo 'Construindo o código...'
                sh 'echo Hello World > hello.txt'
            }
        }
        stage('Test') {
            steps {
                echo 'Rodando testes...'
                sh 'cat hello.txt'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Fazendo deploy...'
                sh 'echo Deploy completo!'
            }
        }
    }
}
