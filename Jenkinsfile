pipeline {
    agent any 
    stages {
        stage('clone')
      {
       steps{
         sh "git clone    "
        stage('Build') { 
            steps {
                sh " mvn install"
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
