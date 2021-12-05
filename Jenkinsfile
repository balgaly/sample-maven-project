pipeline {
    agent any
    tools {
        maven 'maven3' 
    }
    stages {
        stage('maven install') {
            steps {
                    sh 'mvn clean install!'
            }
        }
    }
}
