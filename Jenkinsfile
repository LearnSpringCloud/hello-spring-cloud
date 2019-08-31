pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        sh '''cd /usr/local/docker/jenkins/jenkins-data/workspace/hello-spring-cloud_master/hello-spring-cloud-eureka
mvn -clean'''
      }
    }
  }
}