node ('linux') {
    checkout scm
    stage('Build') {
        sh './mvnw verify'
    }
    stage('Integration Test') {
        sh 'sleep 12'
    }
    stage('Deploy') {
        sh 'sleep 5'
    }
}