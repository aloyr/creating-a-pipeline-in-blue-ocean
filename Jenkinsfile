pipeline {
  agent {
    docker {
      image 'jenkinsci/slave'
    }
    
  }
  stages {
    stage('build') {
      steps {
        sh 'echo "it works"'
      }
    }
  }
}