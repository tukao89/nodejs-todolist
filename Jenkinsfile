pipeline {
    agent any
    stages {
        stage('Clone code') {
            steps {
                git branch: 'main', url: 'https://github.com/tukao89/nodejs-todolist.git'
            }
        }
        stage('Build image') {
            steps {
                sh 'sudo su'
                sh 'docker build -t nodejs-todolist .'
            }
        }
    }
}
