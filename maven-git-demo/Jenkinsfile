node {
  stage('SCM Checkout'){
    git 'https://github.com/kumareshgupta/maven-git-repo.git'  
  }
  stage('compile-package'){
   sh 'mvn package'
  }

}
