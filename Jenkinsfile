pipeline {
    agent any
    stages {
        stage('Submit Stack') {
            steps {
            sh "aws cloudformation create-stack --stack-name s3bucket --template-body file://simplests3cft.json --region 'us-east-1'"
              //sh "aws cloudformation update-stack --stack-name s3bucket --template-body file://simplests3cft.json --region 'us-east-1'"
              /* this
                 is a
                 multi-ine comment */
            // this is a single line comment
            
              }
             }
            }
            }