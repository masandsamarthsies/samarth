​pipeline {
    agent any
    stages {
        stage('Publish') {
            steps {
                publishHTML([
                    allowMissing: true,
                    alwaysLinkToLastBuild: false,
                    keepAll: false,
                    reportDir: '.',
                    reportFiles: 'file.html',
                    reportName: 'MY HTML PIPE PAGE'
                ])
            }
        }
    }
}
