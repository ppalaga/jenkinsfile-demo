node('maven') {
    stage('Build') {
        echo 'Building...'
    }
    stage('Test') {
        echo 'Testing...'
    }
}
stage ('Promote') {
    input 'Deploy to Production?'
}
node('maven') {
    stage('Deploy') {
        echo 'Deploying...'
    }
}