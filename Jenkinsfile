pipeline {
    agent any 
    stages {
        stage('-----Var_declaration---') { 
            steps {
                sh "var1=one"
                sh "var2=2"
                sh "var3=3"
                def var = "one"
            }
        }
        stage('----printing----') { 
            steps {
              // sh "echo printenv "
                //sh "echo printenv "
                echo ${var}
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
