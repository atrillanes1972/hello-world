pipeline {
    agent { docker { image 'docker:18' } }
    stages {
        stage('test') {
            steps {
                sh 'docker --version'
            }
        }
    }
}
