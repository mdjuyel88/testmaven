pipeline {
  agent any
  stages {
    stage('test') {
      steps {
        sh 'echo "Helo test enveronment'
      }
    }

    stage('devops') {
      steps {
        sh 'echo "hello dev environment"'
      }
    }

    stage('prod') {
      steps {
        sh 'echo "helllo prod environment"'
      }
    }

  }
}