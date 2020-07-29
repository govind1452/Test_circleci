pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        echo '"learning. $BUILD_NUMBER AND $demo"'
        sh 'echo " $BUID_NUMBER and $demo "'
        timeout(time: 3, activity: true, unit: 'MINUTES')
      }
    }

  }
  environment {
    demo = '1'
  }
}