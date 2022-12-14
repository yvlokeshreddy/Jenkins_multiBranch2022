node('built-in') 
{
    stage('ContinuousDownload_loans') 
	{
    git 'https://github.com/yvlokeshreddy/maven.git'
	}
    stage('Continuousbuild_loans') 
	{
    sh label: '', script: 'mvn package'
	}
    	
}
