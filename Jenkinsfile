pipeline {
  agent any
  stages {
    stage('mvnbuild') {
      steps {
        bat 'mvn clean install'
      }
    }
    stage('end') {
      steps {
        echo 'end of pipeline'
      }
    }
  }
}
