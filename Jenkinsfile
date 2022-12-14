node('master')

{

stage('ContinuousDownload_master')
         {
    git 'https://github.com/yvlokeshreddy/maven.git'
        }

stage('Continuousbuild_master')
         {
   sh label: '', script: 'mvn package'
        }

}
