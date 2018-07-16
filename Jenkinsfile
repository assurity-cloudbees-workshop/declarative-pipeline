pipeline {
  agent {
    label 'jdk8'
  }
  stages {
    stage('Say Hello') {
      steps {
        echo 'Hello, world!'
        sh 'java -version'
      }
    }
  }
  environment {
    MY_NAME = 'Peter-John'
  }
}