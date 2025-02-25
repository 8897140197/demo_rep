pipeline
{
agent any
stages
{
stage('clone')
{
steps{
git 'https://github.com/8897140197/demo_rep.git'
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
