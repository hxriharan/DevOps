pipeline {
    agent any

    stages {
        stage('Git') {
            steps {
                git 'https://github.com/hxriharan/DevOps.git'
                sh 'javac JavaHelloWorld'
                sh 'java JavaHelloWorld'
                
            }
        }
    }
        
    
}
