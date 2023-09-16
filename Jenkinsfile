pipeline {
  agent {label 'windows-1'}
  stages {
    stage('hello') {
      steps {
        bat(label: 'Hello Docker', script: 'echo Hello from pipeline')
      }
    }

  }
}
