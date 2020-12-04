pipeline {
  agent any
  stages {
    stage('Build') {
      steps {
        ansiblePlaybook(playbook: 'sample_playbook/deploy_sample_playbook.yml', inventory: 'hosts', limit: '18.222.14.62')
      }
    }

  }
}