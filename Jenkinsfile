pipeline {
    agent any
    stages {
        stage('Pull Repo') {
            steps {
                git branch: 'main', url: '<repository_url>'
            }
        }
        stage('Execute Script') {
            steps {
                sh './script.sh'
            }
        }
    }
}
