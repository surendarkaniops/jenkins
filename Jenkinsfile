pipeline {
        agent
    {
        node {
        label 'dockerslave-demo'
        }

    }

    agent 
    stages
    {
        stage('Checkout')
        {
            steps
            {
                checkout scm
            }
        }

        stage("Validate testing")
        {
            steps
            {
                echo "slepp start"
                sleep 10

                }
        }
        stage("Run testing")
        {
            steps
            {
                echo "plan testing"
 
                }
        }
    }
}
