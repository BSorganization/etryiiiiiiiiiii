pipeline {
  agent any
  environment {
    KUBE_URL = credentials('KUBE_URL')
    KUBE_TOKEN = credentials('KUBE_TOKEN')
    DOCKER_URL = credentials('DOCKER_URL')
    DOCKER_USERNAME = credentials('DOCKER_USERNAME')
    DOCKER_PASSWORD = credentials('DOCKER_PASSWORD')
  }
  stages {
    stage('Build Image') {
      steps {
        sh 'echo $KUBE_URL '
      }
    }
    stage('Publish Image') {
      steps {
        sh 'docker '
      }
    }
    stage('Deploy') {
      steps {
        sh 'curl'
      }
    }
  }
}
