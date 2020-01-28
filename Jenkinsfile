pipeline {
    agent any
    environment { 
        VAR1 = 'ONE'
        VAR2 = 'TWO'
        VAR3 = 'THREE'
    }
    stages {
        stage('Master1') {
            steps {
                sh 'echo "This is master" | printenv VAR1'
            }
        }
         stage('Master2') {
            steps {
               sh 'echo "This is master" | printenv VAR2'
            }
          } 
        stage('Master3') {
            steps {
                sh 'var34 = "Rajat"'
                sh 'printenv var34'
              sh 'echo "This is master " | printenv VAR3'
            }
        }
    }
}
