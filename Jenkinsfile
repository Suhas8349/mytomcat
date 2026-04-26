pipeline {
    agent any

    stages {
        stage('Checkout') {
            steps {
                git 'https://github.com/Suhas8349/mytomcat.git'
            }
        }

        stage('Build') {
            steps {
                sh 'echo "Build step here"'
            }
        }
    }
}
