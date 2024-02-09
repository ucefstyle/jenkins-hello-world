      pipeline {
          agent any
          stages {
              stage('Build') {
                  steps {
                      script {
                          // Choisissez la commande en fonction de votre script
                          sh 'Hello.py' // Pour Python
                          // sh 'javac HelloWorld.java && java HelloWorld' // Pour Java
                      }
                  }
              }
          }
      }
