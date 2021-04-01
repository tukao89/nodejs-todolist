pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('Create new file') {
            steps {
                sh 'touch abc.txt'
                
                sh 'ls'
                
            }
        }
        stage('Clone code') {
            steps {
                sh 'git clone https://github.com/tukao89/nodejs-todolist tmp && mv tmp/.git . && rm -rf tmp && git reset --hard'
            }
        }
    }
}
