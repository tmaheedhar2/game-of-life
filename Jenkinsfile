pipeline {
    agent {label 'Slave01'}

    stages {
 
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
