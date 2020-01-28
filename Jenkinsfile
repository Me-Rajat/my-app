pipeline {
    agent any
    environment { 
        VAR1 = 'ONE'
        VAR2 = 'TWO'
        VAR3 = 'THREE'
    }
    stages {
        stage('Master1') {
            environment { 
               // VAR2 = 'TWO'
            }
            steps {
                sh 'echo "This is master" | printenv VAR1'
            }
        }
         stage('Master2') {
            environment { 
                //VAR2 = 'TWO'
            }
            steps {
               sh 'echo "This is master" | printenv VAR2'
            }
          } 
        stage('Master3') {
            environment { 
               // VAR2 = 'TWO'
            }
            steps {
              sh 'echo "This is master " | printenv VAR3'
            }
        }
    }
}
