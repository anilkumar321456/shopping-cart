pipeline {
    agent any
    stages {
        stage('Clone') {
            steps {
                sh "git clone https://github.com/anilkumar321456/shopping-cart.git"
            }
        }
        stage('Build') {
            steps {
                sh "mvn package"
            }
        }
        stage('Test') {
            steps {
                echo "testing is done"
            }
        }
        stage('Deploy') {
            steps {
                echo "deploying soon"
            }
        }
    }
}

