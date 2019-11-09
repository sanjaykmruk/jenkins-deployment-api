node {
    def scmVars

    stage('build') {


      scmVars = checkout scm

      // Run Build
      sh 'mvn clean install'
    }
}
