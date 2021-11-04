@Library('piper-lib-os') _
piperPipeline script: this
pipeline
{
    agent{docker{ image: 'maven:3.3.3'}}
    stages
    {
        stage('build')
        {
            steps
            {
                sh 'mvn --version'
            }
        }
    }
}