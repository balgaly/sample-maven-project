pipeline {
    agent any
    tools {
        maven 'Maven_3.5.2' 
    }
    stages {
        stage('maven install') {
            steps {
                    sh 'mvn clean install!'
            }
        }
    }
}
