pipeline {
  
  agent any
  
  stages {
    
    stage("build") {
      steps {
        echo 'This is the building phase'
        mvn compile
      }
    }
    
    stage("test") {
      steps {
        echo 'This is the test phase'
        mvn test
      }
    }
    
    stage("deploy") {
      steps {
        echo 'This is the deploy phase'
        mvn package
      }
    }
  }
}
    
