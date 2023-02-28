pipeline {
    agent any

    stages {
        stage('build') {
            steps {
                echo 'build'
            }
        }
        stage('deploy') {
            steps {
                echo 'deploy'
            }
        }
        stage('test') {
            steps {
                echo 'test'
            }
        }
    }
             post {
                 always {
                    
                        emailext body: 'summary', replyTo: 'mhe2832@gmail.com', subject: 'summary', to: 'mhe2832@gmail.com' //post
                        }
                  }
    
}
