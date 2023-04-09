pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/hxriharan/DevOps.git'
                sh 'javac JavaHelloWorld'
                sh 'java JavaHelloWorld'
                
            }
        }
    }
        
    
}
