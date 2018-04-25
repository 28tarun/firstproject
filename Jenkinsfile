pipeline {
  agent any
  stages {
    stage('Prepration') {
      steps {
        echo 'CODE IS FEACHED FORM THE REPOSTRY'
      }
    }
    stage('Build') {
      steps {
        echo 'Project will be hare'
        bat 'mvn clean package'
      }
    }
    stage('test') {
      steps {
        echo 'testing is start'
      }
    }
    stage('Deploy') {
      steps {
        echo 'Deploy done'
      }
    }
    stage('Deploy Done') {
      steps {
        echo 'Done'
      }
    }
  }
  environment {
    JAVA_HOME = 'C:\\Program Files\\Java\\jdk1.8.0_171'
    MAVEN_HOME = 'C:\\apache-maven-3.5.3'
  }
}