pipeline{
  agent any
  stages{
    stage("verify tooling"){
      steps{
        sh '''
        docker version
        docker info
        docker comoose version
        curl --version
        jq --version
        '''
      }
    }
  }
}