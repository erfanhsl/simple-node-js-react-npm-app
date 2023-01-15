pipeline {
    agent {
        label 'slave'
    }
    stages {
        stage('Build') {
            steps {
                sh 'hostname'
                sh 'pwd'
                sh 'rsync -a * /home/ubuntu/jenkins_rsync_test'
                sh 'cd /home/ubuntu/jenkins_rsync_test && pwd'
            }
        }
        
    }
}
