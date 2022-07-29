pipeline {
   agent any  
   stages { 
     stage("Stage1") { 
	   steps { 
		   bat "mvn test"
		 }
	   }   
	 stage("Stage2") { 
	   steps { 
		   bat "mvn install"
		 }
	   } 
   } 
 }
