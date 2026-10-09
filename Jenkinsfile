

pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                checkout scm
            }
        }

        stage('Run Python') {
            steps {
                sh 'python extract.py'
            }
        }
    }
}


