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
    stage('install') {
      steps {
        ansiblePlaybook installation: 'ansible', inventory: 'hosts', playbook: 'playbook_instalar.yml'
      }
    }
  }
}
