pipeline {
    agent any

    stages {
        stage('checkout') {
            steps {
                git 'https://github.com/varalakshmikonjeti/maven.git'
            }
        }
        stage('build') {
            steps {
                sh 'mvn clean install'
            }
        }
       
    }
}
