node {
    def scmVars

    stage('build') {

      // Use Maven Tool
      env.PATH="${tool 'mvn'}/bin:${env.PATH}"
      scmVars = checkout scm

      // Run Build
      sh 'mvn clean install'
    }
}
