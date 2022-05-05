node('built-in') 
{
    stage('Continuous Download_command') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_command') 
	{
    sh label: '', script: 'mvn package'
	}
}
