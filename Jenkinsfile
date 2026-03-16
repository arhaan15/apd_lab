pipeline {
    agent any

    stages {

        stage('Job 1') {
            steps {
                sh 'mkdir -p JOB_1'
                echo "JOB_1 created"
            }
        }

        stage('Job 2') {
            steps {
                sh 'mkdir -p JOB_1/JOB_2'
                echo "JOB_2 created"
            }
        }

        stage('Job 3') {
            steps {
                sh 'mkdir -p JOB_1/JOB_2/JOB_3'
                echo "JOB_3 created"
            }
        }
    }
}