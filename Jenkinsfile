pipeline {
  
  agent any
  
  tools {
    maven 'Maven 3.8.3'
    jdk 'jdk8'
  }
  
  stages {
    
    stage("build") {
      steps {
        echo 'This is the building phase'
         sh 'mvn -Dmaven.test.failure.ignore=true install' 
      }
    }
    
    stage("test") {
      steps {
        echo 'This is the test phase'
      }
    }
    
    stage("deploy") {
      steps {
        echo 'This is the deploy phase'
      }
    }
  }
}
    
