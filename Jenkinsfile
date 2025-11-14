pipeline {
    agent none

    stages {
        stage('Listar arquivos') {
            steps {
                sh('ls -l')
            }
        }
        stage('Maven Clean') {
            agent {
                docker { image 'maven:3.9.11-amazoncorretto-11' }
            }
            steps {
                sh('mvn clean')
            }
        }
    }
}
