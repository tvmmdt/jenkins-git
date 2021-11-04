pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'echo "Hello World 2021.11.04.17.41"'
                sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
