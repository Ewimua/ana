pipeline {
    agent {label 'docker-host'}

    stages {
        stage('git checkout') {
            steps {
                git branch: 'main', url: 'https://github.com/Ewimua/ana.git'
            }
        }
        stage('maven build') {
            steps {
                sh 'pwd && ls -lrt'
            }
        }
    }
}
