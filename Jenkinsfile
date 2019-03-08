node{
  stage('SCM checkout'){
    git 'https://github.com/shrikantsayankar/my-app'
  }
  stage('Compile-Package'){
    // Get mvn path
    def mvnHome = tool name: 'maven3', type: 'maven'
    sh "${mvnHome}/bin/mvn package"
  }
    

}
