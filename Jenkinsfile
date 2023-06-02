pipeline
{
    agent any 
    stages
    {
        stage('Build') 
        { 
         steps
         {
          bat 'javac Hello08.java'
          bat 'java -version'
     
          }
        }
        stage('Run')
        { 
            steps 
            {
               bat 'javac Hello08' 
            }
        }
    }
}
