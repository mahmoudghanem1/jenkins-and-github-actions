pipeline{
    agent{
        label 'aws-agent'
    }
      stages{
    stage('build'){
      steps{
        script{
          sh  'mvn clean package'
        }
      }
    }
  }


}
