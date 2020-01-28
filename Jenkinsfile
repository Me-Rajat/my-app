pipeline {
    agent any
    environment { 
        VAR1 = 'ONE'
    }
    stages {
        stage('Example') {
            environment { 
                VAR2 = 'TWO'
            }
            steps {
                sh 'echo "This is master"| printenv VAR1'
            }
        }
    }
}
