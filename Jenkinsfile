pipeline {
    agent any
    parameters {
        string(name: 'GREETING', defaultValue: 'Hello', description: 'Enter a greeting message')
        choice(name: 'BRANCH', choices: ['master', 'develop'], description: 'Select a branch')
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building..'
                // Here you can find the commands that build your application, such as mvn clean install
            }
        }
     
        stage('Deploy') {
            steps {
                echo 'Deploying..'
                // Application deployment scripts
            }
        }
    }
}
