pipeline {
  agent any
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
