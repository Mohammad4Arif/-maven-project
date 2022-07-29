pipeline {
   agent any  
   stages { 
     stage("Stage1") { 
	   steps { 
		   bat "mvn clean install"
		   echo "stage one completd"
		 }
	   } 
	 }   
	 stage("Stage2") { 
	   steps { 
		   bat "mvn clean install"
		   echo "stage 2 completed"
		 }
	   } 
	 }
   } 
 }
