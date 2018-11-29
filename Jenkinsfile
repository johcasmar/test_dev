pipeline {
  agent none
  stages {
    stage('build') {
      steps {
        build(job: '1', quietPeriod: 1, propagate: true, wait: true)
      }
    }
  }
  environment {
    dev = '1'
  }
}