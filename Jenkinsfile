pipeline {
  agent { label 'master' }
  // tools { maven 'M3' }
  stages {
    stage('Checkout') {
      steps {
        git branch: 'main', url:'https://github.com/tilay25/SpringPetClinic.git'
      }
    }
    stage('Build') {
      steps {
        sh 'echo Building ...'
      }
    }
  }
}
