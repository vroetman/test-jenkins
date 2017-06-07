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
        sh 'id'
        sh 'pwd'
        sh 'ASDF=asfadsf'
        sh 'echo ASDF is $ASDF'
      }
    }
  }
}
