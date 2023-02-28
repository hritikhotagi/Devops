pipeline {
    agent any

    stages {
        stage('apna') {
            steps {
                echo 'Hello World'
            }
        }
        stage('pipeline') {
            steps {
                echo 'Hello World'
            }
        }
        stage('ajay') {
            steps {
                echo 'Hello World'
            }
        }
    }
    post
    {
        always
        {
            emailext body: 'ajaypipeline', subject: 'apnapipeline', to: 'hritikhotagiofficial@gmail.com'
        }
    }
}
