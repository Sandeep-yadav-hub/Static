pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        echo "building"
        sleep 10
      }
    }
    stage('Deploy') {
      steps {
        echo "deploying"
        stageMessage "sample stage message"
      }
    }
  }
}
