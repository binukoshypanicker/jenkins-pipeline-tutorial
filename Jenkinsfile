pipeline {
    //agent any
    agent { node { label 'windows-demo-agent-label' } }
    stages {
        stage('Echo Pipeline Phase') {
            steps {
                echo 'Executing echo statement from GitHub Repository !!!' 
            }
        }
    }
}
