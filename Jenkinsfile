pipeline {
    agent any
    stages {
        stage('Checkout') {
            steps {
                                  checkout([$class: 'GitSCM', 
                          branches: [[name: '*/Java17']], // Specify the branch to checkout
                          userRemoteConfigs: [[url: 'https://github.com/MadhuKeerthana25/Java17.git']]])
                          credentialsId: '105178b5-afa8-4583-8e98-3e519d67864e']])

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
