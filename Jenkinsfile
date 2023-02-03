pipeline{
    agent any
    stages {
        stage('linter'){
            steps {
                cmd 'npm run lint'
            }
        }
        stage('test'){
            steps {
                cmd 'npm run test'
            }
        }
        stage('deploy'){
            steps {
                cmd 'npm start'
            }
        }

    }
}
