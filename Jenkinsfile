pipeline {
  agent any
  stages {
    stage('hello') {
      agent {
        node {
          label 'windows-1'
        }

      }
      steps {
        bat(label: 'Hello Docker', script: 'echo Hello from pipeline')
      }
    }

  }
}