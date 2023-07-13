node('master') 
{
    stage('Continuous Download') 
	{
    git 'https://github.com/KranthiGajjelli/Maven.git'
	}
    stage('Continuous Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
}
