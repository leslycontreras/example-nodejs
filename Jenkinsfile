pipeline {
    agent any

    tools {
        nodejs 'NodeJS18'
    }

    stages {
        stage('Install dependencies') {
            steps {
                sh 'npm install'
            }
        }

        stage('Run Hello World') {
            steps {
                sh 'node index.js'
            }
        }
    }
}
