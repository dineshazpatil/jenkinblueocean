node {

  stage ("name of the stage like start" ) {

      echo "starting"
   } 

  stage ("stage 2") {
     echo "This is stage 2"

   }

   stage ("stage 3") {
    echo "This is stage 3"
    powershell '''
    write-host 'this is test'
    get-service 
    '''
   }  

}
