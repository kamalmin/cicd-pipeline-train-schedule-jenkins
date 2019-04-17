pipeline {
 agent any
 stages {
   stage('Build') {
    steps {
     echo ' Running build Automation'
     sh './gradlew build --no-daemon'
     archiveArtifacts artifacts: 'dist/trainSchedule.zip'
        }
   }
   stage('Test') {
    steps {
     echo 'Hello kamal how do you doing '
     sh 'copy dist/trainSchedule.zip dist/trainSchedule.zip.1'
         }
   }
 }
}

