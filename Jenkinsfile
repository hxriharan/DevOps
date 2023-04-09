pipeline {
    agent any

    stages {
        stage('Shell Script') {
            steps {
                git 'https://github.com/hxriharan/DevOps.git'
                sh 'javac JavaHelloWorld'
                sh 'java JavaHelloWorld'
                
            }
        }
    }
        
    
}
