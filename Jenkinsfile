pipeline {
    agent any

    stages {
        stage('Listar arquivos') {
            steps {
                sh('ls -l')
            }
        }
        stage('Maven Clean') {
            steps {
                sh('mvn clean')
            }
        }
    }
}
