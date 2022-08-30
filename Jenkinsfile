pipeline {
    agent any
    
    stages {
        stage("Maven Build") {
           when {
              branch 'dev'
            }
         steps {
           echo "welcome to jenkins.."
            }
        }
        stage("sonar analysis") {
           when {
              branch 'dev'
            }
         steps {
           echo "welcome to jenkins.."
         }
        }
        stage(" QA analysis") {
           when {
              branch 'test'
            }
         steps {
           echo "welcome to jenkins.."
          }   
       }
        stage(" deploy to production ") {
           when {
              branch 'main'
            }
         steps {
           echo "welcome to jenkins.."
         }
       }
    }
 }
