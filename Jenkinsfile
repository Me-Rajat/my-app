pipeline {
    agent any 
    stages {
        stage('-----Var_declaration---') { 
            steps {
                sh "var1=1"
                sh "var2=2"
                sh "var3=3"
            }
        }
        stage('----printing----') { 
            steps {
                sh "echo 'this is master $var1"
                sh "echo 'this is master $var2"
                sh "echo 'this is master $var3"
            }
        }
        stage('----end----') { 
            steps {
                sh "echo 'Finish'"
            }
        }
    }
}
