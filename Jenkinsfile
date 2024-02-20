pipeline {
  agent any
  tools {
    maven 'Maven3.9'
  }
  stages{
    stage('Build'){
      steps{
        echo 'Hello World'
      }
    }
    stage('Example') {
      steps {
        sh 'mvn --version'
      }
    }
  }
  post {
    always {
      echo 'I will always say hello again'
    }
  }
}
