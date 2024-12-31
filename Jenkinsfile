pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('clone') {
            steps {
                sh 'git clone https://github.com/v-i-k-a-s-1-7/jenkins-practice.git'
            }
        }
    }
}
