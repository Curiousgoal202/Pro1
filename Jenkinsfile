pipeline {
    agent any
    stages {
        stage('Start Web Server') {
            steps {
                script { 
  sh 'nohup python3 -m http.server 8085 --bind 0.0.0.0 > server.log 2>&1 &'
                }
            }
        }
    }
}
