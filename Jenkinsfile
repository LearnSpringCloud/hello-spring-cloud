pipeline {
  agent any
  stages {
    stage('pull') {
      steps {
        sh '''pwd
cd hello-spring-cloud-eureka/
pwd
echo "export MAVEN_HOME=/var/local/apache-maven-3.6.1" >> /etc/profile
echo "export PATH=$MAVEN_HOME/bin:$PATH" >> /etc/profile
source /etc/profile
mvn -v'''
      }
    }
  }
}