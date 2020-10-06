
node {
	
	stage('gitcheckout'){
    git 'https://github.com/javahometech/my-app'
	}
   stage('compliepackage'){
   def mvnHome = tool name: 'maven-mh', type: 'maven'
   sh "${mvnHome}/bin/mvn clean compile"
   }
	
}
   
