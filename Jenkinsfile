
pipeline {
    agent any
    stages{
        stage('Git access'){
            steps{
                git branch : 'master' ,url :'https://github.com/rushii0592/-a-.git'
            }
        }

        stage('Java execution'){
            steps{
                bat 'javac code.java'
                bat 'java code'
            }
        }
        stage('Python execution'){
            steps{
                bat 'python code.py'
            }
        }
    }
}
