pipeline
{
    agent any
    stages
    {
        stage('ContDownload')
        {
            steps
            {
                git 'git@github.com:harsh1695/angular-with-spring-boot-and-mongo.git'
            }
        }
        stage('ContBuild')
        {
            steps
            {
                sh 'mvn clean install -DskipTests'
            }
        }
    }
}   
