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
        stage('test again') {
            steps {
                sh './vendor/bin/phpunit tests'
            }
        }
    }
}