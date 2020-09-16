pipeline {
    agent { label 'master' }
    stages {
        node('python-node-mac') {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "/usr/bin/python /Users/netBrackets/Documents/GitHub/simple-python-pyinstaller-app/sources/script.py"
                sh "/usr/bin/python ./sources/script.py"
                sh "hostname"
                sh "uptime"
            }
          }
        }
    }
}
