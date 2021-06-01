node('Gova1')
{

stage('CheckoutCode')
{
checkout([$class: 'GitSCM', branches: [[name: '*/main']], extensions: [], userRemoteConfigs: [[credentialsId: '145949cf-3ced-4fb1-8af6-2cd8d3f8ffd0', url: 'https://github.com/ugr519/MultiEx1.git']]])
}

stage('Build')
{
bat mvn clean package"
}

}
