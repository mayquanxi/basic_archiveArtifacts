pipeline {
    agent {
        label 'linux'
    }
    stages {
        stage('Build') {
            steps {
                sh 'whoami'
                archiveArtifacts artifacts: '*/target/*.jar', fingerprint: true
            }
        }
    }
}
