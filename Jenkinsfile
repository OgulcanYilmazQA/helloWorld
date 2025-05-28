pipeline {
    agent any

    stages {
        stage('Clone repo') {
            steps {
                git url: 'https://github.com/OgulcanYilmazQA/helloWorld.git', branch: 'main'
            }
        }

        stage('Build') {
            steps {
                echo 'Building project...'
            }
        }
    }
}
