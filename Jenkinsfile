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
                javac HelloWorld.java
                java HelloWorld
            }
        }
     stage('Test Code') {
            steps {
                echo "testing done"
            }
        }
    } 
}
