node('built-in') 
{
    stage('Continuous_ Download') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous_ Build') 
	{
    sh label: '', script: 'mvn package'
	}
}
