node('test-node'){
    def work = workspace
    workspace = env.workspace
    // echo "Current workspace is ${env.WORKSPACE}"
    echo "Current workspace is $WORKSPACE"
    stage('cft template'){
        sh 'chmod +x create-update.sh'
        sh './create-update.sh'
    }
}