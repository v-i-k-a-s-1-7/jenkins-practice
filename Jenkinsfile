pipeline {
    agent {label 'agent1'}

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        stage('clone') {
            steps {
                echo "This stage pulls code from my git repository"
                git url: "https://github.com/v-i-k-a-s-1-7/jenkins-practice.git", branch: "main"
                echo "Cloning successful"            }
        }
    }
}
