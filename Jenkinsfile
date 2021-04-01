pipeline {
    agent any
    stages {
        stage('Clone code') {
            steps {
                sh 'git clone https://github.com/tukao89/nodejs-todolist.git --branch main tmp && mv tmp/.git . && rm -rf tmp && git reset --hard'
            }
        }
    }
}
