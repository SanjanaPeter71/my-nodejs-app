pipeline {

    agent any

    stages {

        stage("build"){

            steps {
                echo 'building the application..'
                nodejs('NodeJS-21.4.0'){
                    sh 'npm install'
                    sh 'npm run start'
                }
            }
        }

        stage("test"){

            steps {
                echo 'testing the application...'
            }
        }

        stage("deploy"){

            steps {
                echo 'testing the application...'
            }
        }

    }
}
