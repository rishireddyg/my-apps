node {
  stage('SCM Checkout'){
    git 'https://github.com/rishireddyg/my-apps'
  }
  stage('Compile-Package'){
    sh 'mvn package'
  }
}
