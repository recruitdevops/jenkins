node('built-in') 
{
    stage('Continuous Download__master') 
	{
    git 'https://github.com/KranthiGajjelli/Maven.git'
	}
    stage('Continuous Build_master') 
	{
    sh label: '', script: 'mvn package'
	}
}

