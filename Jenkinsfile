pipeline {
  agent {
    docker {
      image 'arm64v8/maven:3.6.3-openjdk-11'
      args '--network jenkins-blue-ocean-pet-clinic'
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
