node('node2'){
  currentBuild.result = "SUCCESS"
  stage('Printing hello world'){
    sh 'echo "Hello World"'
  }
  stage('System test'){
    sh 'echo "Running system test"'
  }
  stage('Deploy to prod'){
    sh 'echo "Deployed to production"'
  }
}
