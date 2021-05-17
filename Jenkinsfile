node('master'){
    stage('scm'){
        git 'https://github.com/tmaheedhar2/game-of-life.git'
    }

    stage('build'){
        sh 'mvn package'

    }

    stage('postbuild'){
        junit 'gameoflife-web/target/surefire-reports/*.xml'
        archive 'gameoflife-web/target/*.war'

    }


}
