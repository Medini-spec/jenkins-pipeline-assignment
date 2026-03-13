pipeline {
    agent any

    stages {
        stage('Clone Code') {
            steps {
                git branch: 'develop', url: 'https://github.com/YOUR-USERNAME/jenkins-pipeline-assignment.git'
            }
        }

        stage('Move Files') {
            steps {
                sh 'mkdir -p /tmp/git-files'
                sh 'cp -r * /tmp/git-files/'
            }
        }
    }
}