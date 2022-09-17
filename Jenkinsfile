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
            step {
                sh 'echo "composer instalado"'
            }
        }
    }
}