pipeline{
agent any
stages {
stage{
stage('Compile'){
steps{
sh 'javac HelloWorld.java'
}
}
stage('Run'){
steps {
sh 'java HelloWorld'
}
}
}
}
