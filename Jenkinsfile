pipeline {
  agent any  
  stages {
    stage("build") {
      steps{
        echo "build ..."
        sh "cd SpringBootHelloWorldExample;mvn clean package"
      }
    }
    stage("deploy") {
      steps{
        echo "deploy ..."
      }
    }
  }
}
