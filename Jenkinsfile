pipeline {
    agent any

    stages {
        stage ('Compile Stage') {

            steps {
                sh 'Build'
            }
        }

        stage ('Testing Stage') {

            steps {
               sh 'test'
            }
        }


        stage ('Deployment Stage') {
            steps {
               sh 'deploy'
            }
        }
    }
}
