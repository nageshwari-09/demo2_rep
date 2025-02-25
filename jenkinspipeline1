pipeline
{
agent any 
stages
{
stage('clone')
{
stpes
{
git 'https://github.com/nageshwari-09/demo2_rep.git'
}
}
stage('build')
{
steps{
sh 'javac hello.java'
}
}
stage('run')
{
steps
{
sh 'java hello'
}
}
}
}
