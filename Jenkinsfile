pipeline {
  agent any
  stages {
    stage('version') {
      steps {
        bat 'python --version' // Checks Python version
      }
    }
    stage('hello') {
      steps {
        bat 'C:\Program Files\Python38\python.exe p1.py' 
      }
    }
  }
}
