node('slave01') {
    currentBuild.result = "SUCCESS"
    node('slave01'){
        stages {
            stage('Unit testing') {
            sh 'echo "Unit testing"'
            }
            stage('System tests') {
            sh 'echo "Stage #2 - Unit Tests"'
            }
            stage('Deploy to prod') {
            sh 'echo "Stage #3 - Deploy to prod"'
            }
        }
    }
}
