node{
   stage('SCM Checkout'){
     git 'https://github.com/reechasoni/hello-world'
   }
   stage('Compile-Package'){
    
      def mvnHome =  tool name: 'maven3', type: 'maven'   
      sh "${mvnHome}/bin/mvn package"
}
