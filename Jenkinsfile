ode('built-in') 
{
    stage('Continuous Download_Built_In') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_Built_In') 
	{
    sh label: '', script: 'mvn package'
	}
}
