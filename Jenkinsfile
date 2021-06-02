pipeline {
    agent {label 'Slave01'}
    stage('build'){
        steps{    
        sh 'mvn clean package'
        }
    }
}
