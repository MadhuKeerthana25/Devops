pipeline {
    agent any
     environment {
        GIT_CREDENTIALS = credentials('105178b5-afa8-4583-8e98-3e519d67864e')
    }
    stages {
        stage('Checkout') {
            steps {
                    script {
                    git url: 'https://github.com/MadhuKeerthana25/Java17.git', credentials: GIT_CREDENTIALS, branch: 'Java17'
                    }
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
