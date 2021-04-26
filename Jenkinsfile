pipeline {
    agent any
    
    parameters {
     string(name: 'BRANCH', defaultValue: 'main', description: 'Please enter Branch Name')
  }

    stages {
        stage('Hello') {
            steps {
                echo 'Hello World'
            }
        }
        
        stage('Hello1') {
            steps {
                echo 'Hello World1'
            }
        }
    }
}
