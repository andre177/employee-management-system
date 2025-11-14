pipeline {
    agent {
        docker { image 'maven:3.9.11-amazoncorretto-11' }
    }

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
