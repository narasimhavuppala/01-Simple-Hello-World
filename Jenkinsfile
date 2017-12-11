pipeline {
  agent any
  stages {
    stage('Checkout') {
      steps {
        git(url: 'https://github.com/narasimhavuppala/01-Simple-Hello-World.git', branch: 'master', changelog: true)
      }
    }
    stage('Build') {
      steps {
        bat 'echo hello world'
      }
    }
  }
}