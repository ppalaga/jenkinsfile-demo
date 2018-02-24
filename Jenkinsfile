node('maven') {
    stage('Build') {
        echo 'Building...'
    }
    stage('Test') {
        echo 'Testing...'
    }
}
stage ('Promote') {
    timeout(time: 5, unit: 'SECONDS') {
        input 'Deploy to Production?'
    }
}
node('maven') {
    stage('Deploy') {
        echo 'Deploying...'
    }
}