pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "python script.py"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
