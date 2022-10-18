pipeline { 
agent any 
    stages { 
        stage ('Checkout') { 
            steps {
                sh "git clone https://github.com/Gururaj1119/hello-world-war.git"
            }
        }
        stage ('Test') { 
             steps {
                echo "Testing"
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
