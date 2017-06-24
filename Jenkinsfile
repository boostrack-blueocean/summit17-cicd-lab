pipeline {
  agent {
    docker {
      image 'maven:3-alpine'
//      args '-v /Users/hflambo/.m2:/root/.m2'
    }
    
  }
  stages {
    stage('Build App') {
      steps {
        sh 'echo "Build App"'
      }
    }
  }
}
