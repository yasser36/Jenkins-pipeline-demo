pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo 'build complited'
        timeout(time: 5, unit: 'SECONDS') {
          sh "sleep 10"
        }
      }
    }

    stage('Test') {
      steps {
        echo 'test complited'
      }
    }

    stage('Deploy') {
      steps {
        echo 'deploy complited'
      }
    }

  }
}