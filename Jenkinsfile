pipeline {
    agent {
        label 'slave'
    }
    stages {
        stage('Build') {
            steps {
                sh 'hostname'
                sh 'pwd'
                sh 'rsync -a Demo Pipeline/ /home/ubuntu/jenkins_rsync_test'
            }
        }
        
    }
}
