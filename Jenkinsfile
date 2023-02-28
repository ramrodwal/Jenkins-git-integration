pipeline { 
    agent any
    stages {
        stage('Clone Git') {
            steps {
                git 'https://github.com/ramrodwal/Jenkins-git-integration.git'
            }
        }
        stage('Build Code') {
            steps {
                sh "chmod u+x"
                sh "javac HelloWorld.java"
                sh "java HelloWorld"
            }
        }
     stage('Test Code') {
            steps {
                echo "testing done"
            }
        }
    } 
}
