pipeline
{
    agent any
    stages
    {
        stage('ContinuousDownload_loans')
        {
            steps
            {
                git 'https://github.com/intelliqittrainings/maven.git'
            }
        }
        stage('ContinuousBuild_loans')
        {
            steps
            {
                sh 'mvn package'
            }
        }
 }}
