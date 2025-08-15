pipeline {
    agent any
    stages {
        stage('Start Web Server') {
            steps {
                script {
                    sh 'nohup python3 -m http.server 8085 > server.log 2>&1 &'
                }
            }
        }
    }
}
