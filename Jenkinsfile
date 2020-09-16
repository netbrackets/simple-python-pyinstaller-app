pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "/usr/bin/python sources/script.py"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
