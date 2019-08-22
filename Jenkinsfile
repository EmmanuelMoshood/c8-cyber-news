pipeline    {
    agent any

    tools {nodejs "node"}

    stages {
        stage('Fetch code') {
            steps {
                git 'https://github.com/EmmanuelMoshood/c8-cyber-news.git'
            }
        }
         stage('Build') {
            steps {
                sh 'npm build'
            }
        }
    }
}