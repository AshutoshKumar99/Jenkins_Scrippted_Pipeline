node('master')
{

stage('Checkout code from github')
{

git 'https://github.com/AshutoshKumar99/Jenkins_Scrippted_Pipeline.git'

}


stage('Build the project')
{

bat 'mvn clean install'

}



}