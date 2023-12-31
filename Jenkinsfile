pipeline {
    agent any
     environment {
        GIT_CREDENTIALS = credentials('105178b5-afa8-4583-8e98-3e519d67864e')
    }
    stages {
        stage('Checkout') {
            steps {
                    script {
                    git url: 'https://github.com/MadhuKeerthana25/TestJenkins.git', credentials: GIT_CREDENTIALS, branch: 'master'
                    }
            }
        }
        
        stage('Build') {
            steps {
                  script {
                    sh './gradlew clean build'
                }
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
