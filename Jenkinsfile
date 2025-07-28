pipeline {
    agent any
    stages {
        stage('clone the git'){
            steps{
                git 'https://github.com/Sekhar295/simple-java-maven-app.git'
            }
        }
        stage('Build') {
            steps {
                sh 'mvn clean package'
            }
        }
    }
}
