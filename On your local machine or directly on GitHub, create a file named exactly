pipeline {
    agent any
    stages {
        stage('Install Dependencies') {
            steps {
                bat 'npm install'  // Use 'bat' for Windows, 'sh' for Linux
            }
        }
        stage('Run Tests') {
            steps {
                bat 'npm test'
            }
        }
    }
}
