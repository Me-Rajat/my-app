pipeline {
    agent any 
    stages {
        stage('-----Var_declaration---') { 
            steps {
                sh "var1=one"
                sh "var2=2"
                sh "var3=3"
            }
        }
        stage('----printing----') { 
            steps {
              // sh "echo printenv "
                //sh "echo printenv "
                echo "${var1}"
                sh "echo ' printing......."
            }
        }
        stage('----end----') { 
            steps {
                sh "echo 'Finish'"
            }
        }
    }
}
