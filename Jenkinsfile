pipeline {
    agent { docker { image 'gradle' } }
    stages {
        stage('build') {
            steps {
                sh 'echo Hello World!'
                sh 'gradle tasks'
            }
        }
    }
}