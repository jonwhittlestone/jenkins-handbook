pipeline {
    agent { docker { image 'python:3.10.1-alpine' } }
    stages {
        stage('Build') {
            steps {
                sh 'echo "🌈 Hello World"'
		sh '''
                    echo "Multiline shell steps works too"
                    ls -lah
                '''
            }
        }
    }
}
