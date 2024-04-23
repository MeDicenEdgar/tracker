
pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                sh '''
                java -version
                javac Main.java
                java Main
                '''
            }
        }
    }
}
