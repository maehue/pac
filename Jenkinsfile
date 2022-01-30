pipeline {
    agent {
        node {
            label 'workers'
        }
    }    
    stages{
        stage('step 1') {
            steps {
                echo "you are here"
            }
        }
    }
    post {
        always {
            echo 'Cleaning up workspace'
        }
        success {
            echo "${env.JOB_NAME} Successful build"
        }
    }
}