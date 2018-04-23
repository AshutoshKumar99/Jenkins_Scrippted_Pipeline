node('flower')
{

stage('Print Project name')
{
 echo 'This is the simple jenkins project'
}


stage('Checkout code from github')
{

git 'https://github.com/AshutoshKumar99/Jenkins_Scrippted_Pipeline.git'

}


stage('compile stage')
{

bat 'mvn clean compile'

}

stage('Testing stage')
{

bat 'mvn test'

}

stage('Build stage')
{

bat 'mvn clean install'

}


}