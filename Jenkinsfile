pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git 'https://github.com/hxriharan/DevOps.git'
                bat 'javac JavaHelloWorld'
                bat 'java JavaHelloWorld'
                
            }
        }
    }
        
    
}
