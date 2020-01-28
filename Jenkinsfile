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
                sh 'printenv VAR1'
            }
        }
    }
}
