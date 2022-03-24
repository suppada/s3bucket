pipeline {
    agent {
        label 'validations'
    }
    stages{
        stage('cft template'){
            steps{
                sh 'chmod +x create-update.sh'
                sh './create-update.sh'
            }
        }
    }
}