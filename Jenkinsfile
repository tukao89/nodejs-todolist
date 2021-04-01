pipeline {
    agent { 
        label 'jenkin-slave-node' 
    }

    stages {
        stage('Clone code') {
            steps {
                sudo git 'https://github.com/tukao89/nodejs-todolist'
            }
        }
    }
}
