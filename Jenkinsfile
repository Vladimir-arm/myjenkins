pipeline {
    agent any 
    stages {
        stage('Java compile') { 
            steps {
                echo 'Hello, Java'
		sh 'java -version'
            }
        }
        stage('Run Java project') { 
            steps {
                echo 'Hello, JDK'
            }
        }
    }
}
