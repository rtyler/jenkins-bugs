pipeline {
  agent {
    dockerfile { dir 'whale time' }
  }
  stages {
    stage('Example') {
      steps {
        echo 'Hello World!'
        sh 'echo myCustomEnvVar = $myCustomEnvVar'
      }
    }
  }
}
