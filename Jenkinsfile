// Declarative //
pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/maksudacse5737/calculator.git'
                echo 'Building..'
            }
        }
        stage('Test') {
            steps {
                echo 'Testing..'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Deploying....'
            }
        }
    }
}
// Script //
node {
    stage('Build') {
        git 'https://github.com/maksudacse5737/calculator.git'
        echo 'Building....'
    }
    stage('Test') {
        echo 'Building....'
    }
    stage('Deploy') {
        echo 'Deploying....'
    }
}
