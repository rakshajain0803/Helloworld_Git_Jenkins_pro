node
{
stage('access git repository')
{
git 'https://github.com/rakshajain0803/Helloworld_Git_Jenkins_pro.git'
}
stage('compile-package')
{
sh 'mvn package'
}
  stage('Deploy')
  {
  sh 'echo "Done execution"'
  }
}
