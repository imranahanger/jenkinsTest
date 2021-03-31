pipeline {

    agent any
    
    stages{
        
        stage("build"){

            steps {
                echo "this is build stage"
            }
        }

        stage("test"){

            steps {
                echo "this is test stage"
            }
        }
        
        stage("deploy"){

            steps {
                echo "this is test deployment stage"
            }
        }
    }
    post {
        always {
            echo "run always"
        }
        success {
            echo "suceeded"
        }
        failure {
            echo "failure"
        }
    }
}
