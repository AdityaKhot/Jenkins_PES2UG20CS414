pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                sh 'g++ -o PES2UG20CS414-1 567 786 ew.cpp'
                echo "Build Successful"
            }
        }
        stage('Test') {
            steps 
             './PES2UG20CS414-1'
            }
        }
    }
    post {
        always {
            echo 'Pipeline completed'
        }
        failure {
            echo 'Pipeline failed'
        }
    }
}
