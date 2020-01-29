pipeline {
    agent any
    environment { 
        VAR1 = 'ONE'
        VAR2 = 'TWO'
        VAR3 = 'THREE'
    }
    stages {
        stage('Master1') {
           when  {
                 expression{choice == '1'}
            steps {
                sh 'echo "This is master ${VAR1}"'
            }
        }
        }
         stage('Master2') {
             when 
             {
                 expession{choice == '2'}
            {
            steps {
               sh 'echo "This is master ${VAR2}"'
            }
            }
          } 
        stage('Master3') {
             when  {
                 expression{choice == '3'}
           
            steps {
              sh 'echo "This is master ${VAR3}"'
            }
            }
        }
    }
}
