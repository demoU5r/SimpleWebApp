node {
   stage('Preparation') {
      git 'git@github.com:demoU5r/SimpleWebApp.git'
   }
   stage('Build') {
      sh "./gradlew clean test"
   }
}