pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh '''
        ls
        pwd
        echo "Welcome"
        uname
        hostname
        '''
      }
    }
    stage('Test') {
      steps{
        echo "Siuu"
        echo "Siuuuuu"
      }
    }
    stage ('Deploy') {
      steps {
        echo "End"
      }
    }
  }
}
