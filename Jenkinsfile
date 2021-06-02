pipeline {
    agent {label 'Slave01'}

    stages {
        stage('scm') {
            steps {
                git 'https://github.com/tmaheedhar2/game-of-life.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean package'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
