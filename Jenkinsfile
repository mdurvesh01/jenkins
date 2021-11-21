pipline {
  agent {
    dockerfile true
  }
  stages {
    stage('Example') {
      steps {
        echo 'Hellow World'
        sh 'echo myCustomerEnvVar = $myCustomerEnvVar'
      }
    }
  }
}
