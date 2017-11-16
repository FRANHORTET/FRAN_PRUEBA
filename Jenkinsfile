node {
  
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/FRANHORTET/FRAN_PRUEBA'

   }
   stage('read fichero') {
      // Run the maven build
      
      sfichero = readfile 'README.md'
      echo sfichero
      
   }
   
}
