pipeline {
  agent { node { label 'slave-build-node' } }
  stages {
  
    stage('Install Dependencies') {
      steps {
         sh 'echo "installing dependencies"'
         }
      }
      
    stage('Test') {
      steps {
         sh 'echo "testing application..."'
         }
      }
      
    stage('build') {
      steps {
         sh 'echo "building..."'
         }
       }
       
    stage('Deploy application') {
      steps {
         sh 'sudo cp -r * /var/www/demo'
         }
       }
       
     }
    }
