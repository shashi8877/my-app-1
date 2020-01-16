node{

stage('SCM Checkout'){

   git 'https://github.com/shashi8877/my-app-1'

}

stage('Compile-Package'){
def mvnHome = tool name: 'Maven_3_6_3', type: 'maven'

sh "${mvnHome}/bin/mvn package"

}

}
