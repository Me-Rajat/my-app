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
              sh 'echo "Database engine is ${VAR3}"| printenv VAR3'
            }
        }
    }
}
