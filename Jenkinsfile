pipeline {
    agent any

    stages {
        stage('Checkout Code') {
            steps {
                // Haal de code op van GitHub
                checkout scm
            }
        }
        stage('Build') {
            steps {
                // Simuleer een build door een bestand aan te maken
                sh 'echo "Building the project..." > build.log'
            }
        }
        stage('Test') {
            steps {
                // Simuleer een test door een bericht te loggen
                sh 'echo "Running tests..." > test.log'
            }
        }
    }

    post {
        always {
            echo 'Pipeline voltooid.'
        }
    }
}
// test demo klas 