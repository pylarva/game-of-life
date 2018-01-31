pipeline {
  agent any
  stages {
    stage('build') {
      steps {
        sh '/usr/local/maven/bin/mvn clean package'
      }
    }
    stage('test') {
      steps {
        sh '/usr/local/maven/bin/mvn test'
      }
    }
    stage('deploy') {
      steps {
        sh 'echo "start deploy..."'
      }
    }
  }
}