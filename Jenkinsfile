pipeline {
    agent { node { label 'mini2019' } }
    stages {
        stage('build') {
            steps {
                echo "Hello World!"
                sh "/usr/bin/python /Users/netBrackets/workspace/simple-python-pyinstaller-app/sources/script.py"
                sh "/usr/bin/python ./sources/script.py"
                sh "hostname"
                sh "uptime"
            }
        }
    }
}
