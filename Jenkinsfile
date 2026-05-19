pipeline {
    agent any
    environment {
        PATH ="/opt/maven/bin:$PATH"
    }
    Stages{
        stage('biuld'){
            steps{
                sh 'mvn clean install'
            }
        }
    }
}
