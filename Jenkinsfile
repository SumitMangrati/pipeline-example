pipeline {

    agent any

    stages{

        stage("Compile"){

            sh 'javac Test.java'
        }
        stage("run"){

            sg 'java Test'
        }
    }
}