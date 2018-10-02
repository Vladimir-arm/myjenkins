pipeline {
    agent any 
    stages {
        stage('Java compile') { 
            steps {
                echo 'Compiling Java...'
		sh 'java -version'
                sh 'javac HelloWorld.java'
            }
        }
        stage('Run Java project') { 
            steps {
                echo 'Running Hello World project'
		sh 'java HelloWorld'
            }
        }
    }
}
