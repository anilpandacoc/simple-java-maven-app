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
            steps{
            sh "mvn clean install"
            }
        }
    }
}
