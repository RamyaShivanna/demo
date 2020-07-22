pipeline {
    agent none 
    stages {
        stage('Example Build') {
            agent { label 'jenkins-slave-1' } 
            steps {
                 sh 'sh /home/ec2-user/file1.sh'
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
