pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo '"learning. $BUILD_NUMBER AND $demo"'
        sh 'echo " $BUID_NUMBER and $demo "'
      }
    }

  }
  environment {
    demo = '1'
  }
}