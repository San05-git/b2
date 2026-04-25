pipeline{
  agents any
  stages{
    stage('Build'){
      steps{
        sh 'docker build -t sannidhi005/myapp2:v1'
      }
    stage('Push'){
      steps{
        sh 'docker push sannidhi005/myapp2:v1'
      }
    }
    }
  }
}
