pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        sh '''pwd
cd hello-spring-cloud-eureka/
pwd
/var/local/apache-maven-3.6.1/bin/mvn -v
'''
      }
    }
  }
}