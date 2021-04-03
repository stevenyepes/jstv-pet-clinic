pipeline {
  agent {
    docker {
      image 'arm32v7/maven:3.6.3-adoptopenjdk-11'
    }

  }
  stages {
    stage('Build') {
      steps {
        sh 'mvn package'
      }
    }

  }
}
