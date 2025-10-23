pipeline {
  agent any
  tools {
    jdk 'jdk17'
    maven 'Maven 3.8.7'
  }
  stages {
    stage('Verify Setup') {
      steps {
        sh 'java -version'
        sh 'mvn -version'
        sh 'git --version'
      }
    }
  }
}
