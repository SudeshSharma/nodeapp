pipeline {
  agent any

  tools {nodejs "node"}

  stages {    
    stage('Cloning Git') {
      steps {
        git 'https://github.com/SudeshSharma/nodeapp.git'
      }
    }        
     
    stage('Test') {
      steps {
         sh 'npm test'
      }
    }             
  }
}
