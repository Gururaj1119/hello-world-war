pipeline { 
    agent { label 'slave1' } 
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
                sh "cd hello-world-war"
                sh "mvn clean package"
             }
        }
        stage ('Deploy') { 
             steps {
                sh "ls"
                sh "cp -R /home/slave1/workspace/hellopipe/target/hello-world-war-1.0.0.war /opt/tomcat/webapps"
             }
        }
 
    }           
 }
