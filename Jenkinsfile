pipeline {
    agent { label 'master' }
    stages {
        stage('build') {
          node('python-node-mac') {
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
