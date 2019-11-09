node {
    def scmVars

    stage('build') {

      // Use Maven Tool
      
      scmVars = checkout scm

      // Run Build
      sh git pull
      sh 'mvn clean install'
    }

    stage('Deploy') {

       
      }
   }
}
