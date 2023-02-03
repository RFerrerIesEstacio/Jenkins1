pipeline{
    agent any
    tools { nodejs "node", jdk "jdk" }
    stages {
        stage('linter'){
            steps {
                sh 'npm i'
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
