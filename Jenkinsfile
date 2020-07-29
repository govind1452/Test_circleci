pipeline {
  agent any
  stages {
    stage('stage1') {
      steps {
        timeout(time: 3, activity: true, unit: 'MINUTES')
        echo '"learning. $BUILD_NUMBER AND $demo"'
        sh 'echo " $BUID_NUMBER and $demo "'
      }
    }

  }
  environment {
    demo = '1'
  }
}