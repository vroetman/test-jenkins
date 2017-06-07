pipeline {
  agent {
    docker {
      image 'centos:7'
    }
    
  }
  stages {
    stage('Stage One') {
      steps {
        sh 'date'
        sh 'whoami'
        sh 'pwd'
      }
    }
  }
}
