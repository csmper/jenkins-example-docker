pipeline {
  agent {
    docker {
      image 'node:16-alpine'
    }
  }
  
  stages {
    stage {
      steps {
        sh 'node --version'
      }
    }
  }
}
