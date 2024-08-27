pipeline {
    agent any
    stages {
            stage ("Building stage"){
                     steps {
                             bat "mvn build"
                     }
            }
            stage ("Deploying stage"){
                     steps {
                             bat "mvn deploy"
                     }
            }
      }
}
