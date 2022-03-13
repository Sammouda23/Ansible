pipeline {
    agent any

    stages {
        stage('clone') {
            steps {
           git 'https://github.com/Sammouda23/Ansible.git'
            }}
            
        stage('Hello') {
            steps {
             sh 'ansible-playbook -i hosts worker.yml'
            }
        }
    }
}
