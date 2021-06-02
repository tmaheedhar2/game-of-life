pipeline {
    agent {label 'Slave01'}
    stage('build'){
        sh 'mvn clean package'
    }
}
