pipeline {
    agent any
    environment {
        BRANCH_NAME = "origin/main"
    }
    stages {
        stage('Clone code') {
            steps {
                sh 'git clone https://github.com/tukao89/nodejs-todolist.git --branch main'
            }
        }
    }
}
