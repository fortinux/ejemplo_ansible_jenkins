pipeline {
  agent any
  stages {
    stage('fetch') {
      steps {
        sh '''
          ansible --version
          ansible-playbook --version
        '''
      }
    }
  }
}
