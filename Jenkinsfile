pipeline {
  // agent { label 'master' }
  agent { label 'ubuntu' }
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
