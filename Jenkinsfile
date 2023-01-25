pipeline {
  agent { docker { image 'python:3.10.6' } }
  stages {
    stage('build') {
      steps {
        sh '''
          ansible --version
          ansible-playbook --version
        '''
      }
    }
  }
}
