pipeline {
    agent any

    stages {

        stage('Stage 1 - Start') {
            steps {
                echo 'Pipeline started'
            }
        }

        stage('Stage 2 - Build') {
            steps {
                echo 'Building application...'
                sh 'echo Build successful'
            }
        }

        stage('Stage 3 - Test') {
            steps {
                echo 'Running tests...'
                sh 'echo Tests passed'
            }
        }

        stage('Stage 4 - Code Analysis') {
            steps {
                echo 'Analyzing code quality...'
                sh 'echo Code analysis done'
            }
        }

        stage('Stage 5 - Package') {
            steps {
                echo 'Packaging application...'
                sh 'echo Package created'
            }
        }

        stage('Stage 6 - Deploy to Staging') {
            steps {
                echo 'Deploying to staging...'
                sh 'echo Deployed to staging'
            }
        }

        stage('Stage 7 - Deploy to Production') {
            steps {
                echo 'Deploying to production...'
                sh 'echo Production deployment complete'
            }
        }

    }

    post {
        success {
            echo 'Pipeline completed successfully!!!!!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
