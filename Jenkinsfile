pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent { label 'master' } 
            steps {
                 echo "nature"
                }
        }
        stage('Example Test') {
             agent { label 'master' }
            steps {
                echo "good day"
            }
        }
    }
}
