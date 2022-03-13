pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                ansiblePlaybook disableHostKeyChecking: true, installation: 'ansible-c', inventory: 'hosts', playbook: 'worker.yml'
            }
        }
    }
}
