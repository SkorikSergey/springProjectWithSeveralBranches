pipeline {
  agent any
  stages {
    stage('shell script') {
      steps {
        sh 'echo \'build project starting\''
      }
    }
    stage('build a job') {
      steps {
        build 'build project'
      }
    }
    stage('end building shell script ') {
      steps {
        sh 'echo \'build project finished\''
      }
    }
  }
}