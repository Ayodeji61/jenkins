pipeline {
    agent {
        node { label 'workstation' }
    }
    environment {
        NEWRELIC_API_KEY = credentials('ansible')
    }
    stages {
        stage('Foo') {
            steps {
              echo 'Hello world'
            }
        }

        stage('Foo') {
            steps {
               echo 'Hello world'
            }
         }

    }
}