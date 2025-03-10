pipeline {
    agent any
    stages {
        stage('Echo Hello World') {
            steps {
                echo 'Hello, Jenkins!'
            }
        }
        stage('Check System Info') {
            steps {
                sh 'uname -a'
                sh 'whoami'
            }
        }
        stage('Echo World') {
            steps {
                echo 'Hello, Global Hack Week!'
            }
        }
        stage('Echo GHW') {
            steps {
                echo 'Hello again, Global Hack Week!'
            }
        }
        stage('List Files in Workspace') {
            steps {
                sh 'ls -lah'
            }
        }
    }
}
