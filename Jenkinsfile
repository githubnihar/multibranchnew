node('master') 
{
    stage('Continuous Download-loans') 
	{
    git 'https://github.com/githubnihar/maven.git'
	}
    stage('Continuous Build-loans') 
	{
    sh label: '', script: 'mvn package'
	}
}
