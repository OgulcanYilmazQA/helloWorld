pipeline {
    agent any

    stages {
        stage('Clone repo') {
            steps {
                git url: 'https://github.com/OgulcanYilmazQA/helloWorld.git'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
