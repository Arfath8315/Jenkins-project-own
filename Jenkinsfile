pipeline {
    agent any

    stages {
        stage('Clone Repo') {
            steps {
                git branch: 'main',
                url: 'https://github.com/<your-username>/jenkins-java-demo.git'
            }
        }

        stage('Build') {
            steps {
                sh 'mvn clean compile'
            }
        }
    }
}

