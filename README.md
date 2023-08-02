# Jenkins_filetest1
pipeline{
  agent any
  stages{
    stage(build){
      steps{echo "this is my first jenkins file build"
      }
    }
    stage (test){
      steps{echo "this is my first jenkins file test"
           }
      }
     stage (deploy){
       steps{echo "this is my first jenkins file deploy"
            }
      }
  
  }
}  
            
      
    
