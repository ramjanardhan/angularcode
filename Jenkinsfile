pipeline {

  agent any
  stages {
    stage('Git Checkout') {
      steps {
               checkout scm 
            }
    }

stage('Node Modules installing') {       
      
       steps     
{	   sh "npm install"                    

}
}
stage('Build application') {       
       steps {
             sh "ng build"                    
}
}    
    
//stage('Sonarqube Coverage') {       
//withSonarQubeEnv('sonarqube') {     
// sh "ng test --code-coverage"                    
// }  
//}
//stage('Sonarqube Total analysis') {       
//withSonarQubeEnv('sonarqube') {     
//sh "npm run sonar"                    
//}  
//}

  }
}
