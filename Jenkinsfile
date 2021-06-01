node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/lakshmipathi18/maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
