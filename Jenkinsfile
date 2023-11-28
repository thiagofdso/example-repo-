pipeline {
    agent any
    
    stages {
        stage('info') {
            steps {
                // Checkout the master branch
                script {
                    checkout scm
                
                // Run the git log command
                    sh 'git log'
                }
            }
        }
    }
}
