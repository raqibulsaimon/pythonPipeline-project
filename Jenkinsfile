pipeline
{
  agent
  {
    label 'slave1'
  }
  stages
  {
      stage('Build')
      {
        steps
        {
          sh 'pwd'
          sh 'touch abc.txt'
        }
      }

      stage ("Test")
      {
        steps
        {
            sh 'echo "Testing the code"'
        }
      }

  }
}
