node('master') 
{
    stage ('continuous Download')
    {
        git 'https://github.com/arun-gupta/docker-java-sample.git'
    }
    stage('continiuous build')
    {
        sh 'mvn package'
    }
 }       
