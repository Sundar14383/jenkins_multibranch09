node('master') 
{
    stage('Continuous Download_Sales') 
	{
    git 'https://github.com/sunildevops77/maven.git'
	}
    stage('Continuous Build_Sales') 
	{
    sh label: '', script: 'mvn package'
	}
    	
}
