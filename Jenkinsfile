pipeline {
    agent {
        node {
            label 'maven-slave'
        }
        
    }

    stages {
        stage('Clone-Code') {
            steps {
                git branch: 'main', url: 'https://github.com/LokeshReddy180900/tweet-trend-new.git'
            }
        }
    }
}
