pipeline {
    agent jenkin-slave-node

    stages {
        stage('Clone code') {
            steps {
                git 'https://github.com/tukao89/nodejs-todolist'
            }
        }
    }
}
