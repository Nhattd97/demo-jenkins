pipeline {
    agent any
    options {
        skipStagesAfterUnstable()
    }
    stages {
        stage('Test') {
            steps {
                echo 'Testing'
            }
        }
        stage('Build') {
            steps {
                echo 'Building'
            }
        }
        stage('Deploy-develop') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Deploy-staging') {
            steps {
                echo 'Deploying'
            }
        }
        stage('Deploy-onpremise') {
            steps {
                echo 'Deploying'
            }
        }
    }
}