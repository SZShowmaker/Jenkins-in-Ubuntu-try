pipeline {
    agent any
    stages {
        stage('build') {
            steps {
                sh 'g++ helloworld.cpp -o helloworld'
                sh './helloworld'
            }
        }
    }
}
