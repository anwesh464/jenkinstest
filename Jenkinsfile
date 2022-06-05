node {
  stage('Checkout') {
    checkout scm
  }
  stage('Build') {
    echo "Building ${env.BUILD_ID} on ${env.JENKINS_URL}"
  }
  stage('Test') {
      echo 'Testing....'
  }
  stage('Deploy') {
      echo 'Deploying....'
  }
}
