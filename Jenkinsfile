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
                sh 'docker build -t nodejs-todolist .'
            }
        }
    }
    post { 
        always { 
            emailext body: 'xxxx', subject: 'aaaa', to: 'tu.phunganh@gmail.com'
        }
    }
}
