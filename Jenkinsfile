pipeline{
  agent any
  stages{
    stage("Build"){
      steps{
        build 'PES1UG21CS851-1'
        sh 'g++ hello.cpp -o hello'
      }
    }
    stage("Test"){
      steps{
        sh './abhvhvhvhcde'
      }
    }
    stage("Deploy"){
      steps{
        echo 'Deploy'
      }
    }
  }
  post{
    failure{
      error 'Pipeline failed'
    }
  }
}
