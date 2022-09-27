pipeline {
  agent any  
  stages {
    stage("build") {
      steps{
        echo "build ..."
        sh "cd json-jdbc-server;mvn clean package"
      }
    }
    stage("deploy") {
      steps{
        echo "deploy ..."
      }
    }
  }
}