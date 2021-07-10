pipeline{
    agent{
        label "agent2"
    }
    stages{
        stage('Checkout'){
            steps {
                checkout scm
            }
        }
        stage('Build'){
            sh "mvn clean install"
        }     
    }
}
