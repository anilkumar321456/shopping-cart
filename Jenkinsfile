pipeline {
    agent any
    stages {
        // stage('Clone') {
        //     steps {
        //         sh "git clone https://github.com/anilkumar321456/shopping-cart.git"
        //     }
        // }
        stage('Build') {
            steps {
                sh "mvn install"
            }
        }
        stage('Test') {
            steps {
               sh " echo testing is done"
            }
        }
        stage('Deploy') {
            steps {
                sh "echo deploying soon"
            }
        }
    }
}

