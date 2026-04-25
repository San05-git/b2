pipeline {
  agent any

  stages {

    stage('Build') {
      steps {
        bat 'docker build -t sannidhi005/myapp2:v1 .'
      }
    }

    stage('Login') {
      steps {
        bat 'docker login -u sannidhi005 -p YOUR_PASSWORD'
      }
    }

    stage('Push') {
      steps {
        bat 'docker push sannidhi005/myapp2:v1'
      }
    }

  }
}
