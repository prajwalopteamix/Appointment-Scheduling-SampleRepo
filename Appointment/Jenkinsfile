pipeline
{
    agent none
    stages
    {
        stage('Compile')
        {
            steps
            {
                // hecking out the code from Github
                sh 'git checkout master'
            }
        }
        stage('Test')
        {
            steps
            {
                //executing the test cases written
                sh 'mvn test'
            }
        }
    }
}
