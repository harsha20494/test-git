pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        sh 'echo $Name'
        build(job: 'h', propagate: true, quietPeriod: 1, wait: true)
      }
    }

  }
}