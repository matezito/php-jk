pipeline {
    agent any
    options {
        timeout(time: 2, unit: 'MINUTES')
    }
    stages {
        stage('install') {
            steps {
                sh 'composer install'
            }
        }
        stage('test shell') {  
            steps {
                sh 'echo "composer instalado"'
            }
        }
    }
}