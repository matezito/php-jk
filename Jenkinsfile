pipeline {
    agent any
    options {
        timeout(time: 2, unit: 'MINUTES')
    }
    stages {
        stage('install') {
            step {
                sh 'composer install'
            }
        }
        stage('test shell') {  
            step {
                sh 'echo "composer instalado"'
            }
        }
    }
}