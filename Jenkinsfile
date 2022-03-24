pipeline {
    agent {
        label 'validations'
    }
    stages{
        stage('cft template'){
            steps{
                sh 'pwd && ls'
                sh 'chmod +x 700 create-update.sh'
                sh './create-update.sh'
            }
        }
    }
}