pipeline {
    agent { 
      
        docker { 
            image 'python:3.5.1' 
            customWorkspace /C/Users/bacsi/.jenkins/workspace/test2pipeline_master
        } } 
    stages {
        stage('build') {
            steps {
                sh 'python --version'
            }
        }
    }
}

