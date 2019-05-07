pipeline {
  agent {
    kubernetes {
      label 'kube'
    }
  }

  stages {
    stage('Build') {
      steps {
          echo 'Building..'
      }
    }
    stage('Test') {
      steps {
          echo 'Testing..'
          docker info
      }
    }
    stage('Deploy') {
      steps {
          echo 'Deploying....'
      }
    }
  }
}