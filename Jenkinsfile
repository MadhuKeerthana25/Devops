pipeline {
    agent any
    parameters{ 
      string defaultValue: 'Keerthana', description: 'Choose your name', name: 'name'
}
    stages {
        stage('Checkout') {
            steps {
                checkout scm
            }
        }
        
        stage('Build') {
            steps {
                // Your build steps go here
            }
        }
        
        stage('Test') {
            steps {
                // Your test steps go here
            }
        }
        
        stage('Deploy') {
            steps {
                // Your deployment steps go here
            }
        }
    }
}
