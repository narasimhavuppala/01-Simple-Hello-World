pipeline {
  agent {
    node {
      label 'master'
    }
    
  }
  stages {
    stage('checkout') {
      steps {
        git(url: 'git@github.com:narasimhavuppala/01-Simple-Hello-World.git', branch: 'master')
      }
    }
  }
}