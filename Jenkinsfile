pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                retry(3) {
                    sh 'echo "Hello world"'
                }
                sh '''
                    echo "Multiline step works too"
                    ls -lah
                    echo "ola"
                '''
            }
        }
    }
}
