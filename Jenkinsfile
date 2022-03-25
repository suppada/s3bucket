pipeline {
    agent {
        label 'test-node'
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