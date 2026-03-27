pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Build en cours...'
            }
        }
        stage('Test') {
            steps {
                echo 'Tests en cours...'
            }
        }
        stage('Execution Script') {
            steps {
                sh './test.sh'
            }
        }
        stage('Deploy') {
            steps {
                echo 'Déploiement simulé...'
            }
        }
    }
}
