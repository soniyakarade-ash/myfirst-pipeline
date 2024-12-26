pipeline   	                                      //it starts with pipeline keyword
{
 agent any   	                                      //any: run stages on any available agent
 stages      	                                      //it contains stages

  {
   stage ('print something')            	  //stage name
   { steps { sh 'echo Hello_Jenkins' } }
  }

 {
   stage ('build project')            	  //stage name
   { steps { sh 'echo build project' } }
  }
 {
   stage ('deploy project')            	  //stage name
   { steps { sh 'echo deploy project' } }
  }
}
