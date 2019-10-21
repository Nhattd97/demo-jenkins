pipeline {
  agent any
  stages {
    stage('Test') {
      parallel {
        stage('Test') {
          steps {
            echo 'Testing'
          }
        }
        stage('test success') {
          steps {
            sh 'echo "Hello Nhat"'
          }
        }
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
  options {
    skipStagesAfterUnstable()
  }
}