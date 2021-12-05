pipeline {
    agent any
    tools {
        maven 'Maven3' 
    }
    stages {
        stage('maven install') {
            steps {
                    sh 'mvn clean install!'
            }
        }
    }
}
