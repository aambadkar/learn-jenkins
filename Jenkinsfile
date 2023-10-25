pipeline {
  agent any
  stages {


   environment{
     sample_url = "http://sample.com"
     SSH = credentials("ssh")
   }

    stage('one'){
      steps {
        sh 'echo one'
        sh 'echo ${sample_url}'
        sh 'echo $SSH'

      }
    }

    stage('two') {
      steps {
        sh 'echo two'
      }
    }
 }

}