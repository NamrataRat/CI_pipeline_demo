pipeline {
  agent any
  stages {
        
    stage('Git') {
      steps {
        git 'https://github.com/NamrataRat/CI_pipeline_demo.git'
      }
    }
     
    stage('Build') {
      steps {
        sh 'npm install'
         sh 'npm start'
      }
    }  
  }
}