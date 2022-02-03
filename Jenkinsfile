pipeline {
  agent {
    docker {
      image "node:alpine"
      args "--network=skynet"
    }
  }
  stages {
    stage("Build") {
      steps {
        
        sh "npm install"
      }
    }
   
   
     
  }
}
