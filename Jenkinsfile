pipeline {
  agent {
    docker {
      image 'maven:3.6.3-openjdk-11'
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