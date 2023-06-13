pipeline {
    agent {
        node {
            label 'ansible'
        }
    }

    stages{

        stage('Execute Ansible Playbook file or deploy webapp'){
            steps{
                sh "ansible-playbook deploy.yml"
            }
        }
    }
}
