pipeline
{
  agent any
  stages
  {
    
    stage ('git-clone')
    { steps 
     {sh 'echo downloading code'}
    }
  
    stage ('code compile')
    { steps
     {sh 'echo code is compiling'}
    }
    
    stage ('build')
    { steps
     {sh 'echo code is build'}
    }
    
     stage ('get approval')
    { input "please approve the deployment?"}
    
      stage ('deploy')
    { steps
     {sh 'echo code is deploy'}
    }
  }
}
