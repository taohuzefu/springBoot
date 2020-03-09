pipeline {
   node(jenkins-slave-node)

   stages {
      stage('Clone') {
         steps {
            sh 'node --version'
            git 'https://github.com/taohuzefu/springBoot.git'
         }

      }
      stage('Build') {
            steps{
                echo 'This is a build step'
            }
        }
        stage('Test') {
            steps{
                echo 'This is a test step'
            }
        }
        stage('Deploy') {
            steps{
                echo 'This is a deploy step'
            }
        }
   }
}
