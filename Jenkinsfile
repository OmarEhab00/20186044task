pipeline {
    agent any
    stages {
        stage('Pull Repo') {
            steps {
                git branch: 'main', url: 'https://github.com/OmarEhab00/20186044task.git'
            }
        }
        stage('Execute Script') {
            steps {
                sh './ls.sh'
            }
        }
    }
}
