pileline{
   agent any
     stages{
       stage(git_checkout){
       	steps{
          git credentialsId: 'open-git', url: 'https://gitlab.com/Datanomist123/a_branch_test.git'
       }    
     }
	   stage(clean){
       	steps{
          sh "mvn clean install"
       }    
     }
}
}
