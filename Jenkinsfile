pipeline {
  agent any
  environment {
      DEBUG=false
  }
  stages {
    stage('hello') {
      steps {
        sh 'echo "Debug is currently set to $DEBUG"'
      }
    }
  }
}
