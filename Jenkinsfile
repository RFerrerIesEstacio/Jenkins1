pipeline{
    agent any
    stages {
        stage('install') {
            steps {
                sh 'npm install'
            } 
        }
        stage('linter'){
            steps {
                sh 'npm run lint'
            }
        }
        stage('test'){
            steps {
                sh 'npm run test'
            }
        }
        stage('deploy'){
            steps {
                sh 'npm start'
            }
        }

    }
}
