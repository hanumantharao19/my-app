
node {
 
   stage('compliepackage'){
   def mvnHome = tool name: 'maven-mh', type: 'maven'
   sh "${mvnHome}/bin/mvn install package"
   }
	
}
   
