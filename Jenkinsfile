pipeline   	                                      //it starts with pipeline keyword
{
 agent any   	                                      //any: run stages on any available agent
 stages      	                                      //it contains stages

  {
   stage ('print something')            	  //print
   { steps { sh 'echo Hello_Jenkins' } }
  }

 {
   stage ('build project')            	  //build
   { steps { sh 'echo build project' } }
  }
 {
   stage ('deploy project')            	  //deploy
   { steps { sh 'echo deploy project' } }
 }
}
