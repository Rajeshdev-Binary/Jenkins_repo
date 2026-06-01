pipeline {
    agent {
        docker { image 'alpine:latest' }
    }

    stages {
        stage('Verify Docker Agent') {
            steps {
                echo 'Running inside Docker container...'
                sh 'uname -a'
                sh 'echo "Docker agent is working!"'
            }
        }
    }
}

