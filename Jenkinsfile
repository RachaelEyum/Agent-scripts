pipeline {
   agent any

      stages{
           stage("create zip file"){
               steps{

                   sh 'zip agentScript-${BUILD_NUMBER}.zip * --exclude Jenkinsfile README.md ' 

                }
            }

        }
}