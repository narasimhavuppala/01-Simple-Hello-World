pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git 'https://github.com/narasimhavuppala/01-Simple-Hello-World.git'
      }
    }
  }
}