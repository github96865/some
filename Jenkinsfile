pipeline
{
agent any
options { retry(3) }
stages
{
stage('clone')
{
steps
{
checkout([$class: 'GitSCM', branches: [[name: '*/master']], userRemoteConfigs: [[credentialsId: 'git', url: 'https://github.com/github96865/some.git']]])

    	     }
       }
  }

}
