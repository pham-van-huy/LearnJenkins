pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Building..."'
                sh 'echo "Build finish"'
            }
        }
        stage('Test'){
            steps {
                sh 'echo "Testing..."'
                sh 'echo "Tested finish"'
            }
        }
        stage('Deploy') {
            steps {
                sh 'echo "Deploying..."'
                sh 'echo "Deployed..."'
            }
        }
    }
}
