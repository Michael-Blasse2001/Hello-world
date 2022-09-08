pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo "Hello World"'
        sh '''
          echo "This will list current dir content from latest"
          ls -lh
          echo "New Line"
          '''
      }
    }
    stage ('Test') {
      steps {
        sh 'echo "Hello Test"'
        sh '''
           echo "This lists current dir"
           pwd
           '''
      }
    }
  }
}
