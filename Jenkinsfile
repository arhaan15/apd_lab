pipeline {
    agent any

    stages {

        stage('Pull') {
            steps {
                echo "Pulling code from GitHub"
                checkout scm
            }
        }

        stage('Build') {
            steps {
                echo "Build Stage"
                sh 'chmod +x Build.sh'
                sh './Build.sh'
            }
        }

        stage('Test') {
            steps {
                echo "Test Stage"
                sh 'chmod +x Test.sh'
                sh './Test.sh'
            }
        }

        stage('Deploy') {
            steps {
                echo "Deploy Stage"
                sh 'chmod +x Deploy.sh'
                sh './Deploy.sh'
            }
        }
    }
}
