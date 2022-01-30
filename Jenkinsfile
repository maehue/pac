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
        success {
            echo "${env.JOB_NAME} Successful build"
        }
    }
    
    
}