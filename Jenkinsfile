pipeline {
  agent {
    docker {
      image 'centos:7'
    }
    
  }
  stages {
    stage('Stage One') {
      steps {
        sh '''
          ls
          pwd
          ASDF=onetwothree
          echo $ASDF
          echo \'$ASDF\' "= $ASDF"
          id
          hostname
	  cat /etc/redhat-release'''
      }
    }
  }
}
