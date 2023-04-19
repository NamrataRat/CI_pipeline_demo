


pipeline {
  agent {
        docker {
            image 'node:6-alpine'
            args '-p 3000:3000'
        }
    }
  environment {
        CI = 'true' 
    }

  tools {
        nodejs 'node 7'
    }
  stages {
    stage('Example') {
      steps {
        sh 'npm i'
        sh 'npm start'
      }
    }
  }
}
