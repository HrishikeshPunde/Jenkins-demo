pipeline {

    agent any
    tools {
        maven 'mvn-home' 
     
    }
    stages {
        stage('Compile stage') {
            steps {

                 {
                    sh 'mvn clean compile'
                }
            }
        }

        stage ('Testing Stage') {

            steps {
                 {
                    sh 'mvn test'
                }
            }
        }


        stage ('Deployment Stage') {
            steps {
                 {
                    sh 'mvn deploy'
                }
            }

    }

         stage('testing stage') {
             steps {
                bat "mvn test"
        }
    }

          stage('deployment stage') {
              steps {
                bat "mvn deploy"
        }
    }

  }

}
