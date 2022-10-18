pipeline { 
agent any 
    stages { 
        stage ('Checkout') { 
            steps {
                sh "pwd"
                sh "rm -rf hello-world-war"
                sh "git clone https://github.com/Gururaj1119/hello-world-war.git"
            }
        }
        stage ('Build') { 
             steps {
                sh "ls"
             }
        }
        stage ('QA') { 
             steps {
                echo "QA"
             }
        }
        stage ('Deploy') { 
             steps {
                echo "Deploy"
             }
        }
        stage ('Monitor') { 
             steps {
                echo "Monitor"
             }
        }
 
    }           
 }
