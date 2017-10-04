pipeline {
  agent any
  stages {
    stage('error') {
      steps {
        parallel(
          "error": {
            echo 'hi'
            
          },
          "man": {
            echo 'mvn -v'
            
          }
        )
      }
    }
  }
}