pipeline {
    agent { label 'docker-java' }

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
