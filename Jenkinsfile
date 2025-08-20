pipeline
{
agent any
stages{
stage('checkout'){
steps{
git branch: 'main',url:'https://github.com/ramnath231/ram1.git'
}
}
stage('hello'){
steps{
echo "hello from jenkins pipeline!"
}
}
stage('goodbye'){
steps{
echo "pipeline finished successfully"
}
}
}
}

