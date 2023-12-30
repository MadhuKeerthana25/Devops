pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                                  checkout([$class: 'GitSCM', 
                          branches: [[name: '*/Java17']], // Specify the branch to checkout
                          userRemoteConfigs: [[url: 'https://github.com/MadhuKeerthana25/Java17.git']]])

            }
        }
        
        stage('Build') {
            steps {
                  echo 'Hello, World!'
            }
        }
        
        stage('Test') {
            steps {
                  echo 'Hello, World!'
            }
        }
        
        stage('Deploy') {
            steps {
                 echo 'Hello, World!'
            }
        }
    }
}
