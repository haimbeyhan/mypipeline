node('node2'){
  currentBuild.result = "SUCCESS"
  stage('Unit testing'){
    sh 'echo "Running unit test"'
  }
  stage('System test'){
    sh 'echo "Running system test"'
    exit 1
  }
  stage('Deploy to prod'){
    sh 'echo "Deployed to production"'
  }
}
