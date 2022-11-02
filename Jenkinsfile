pipeline{
    agent any
    stages{
        stage("Build"){
            steps{
                echo "Build ID is ${BUILD_ID}\n"
                echo "Build number is ${BUILD_NUMBER}\n"
            }
        }
        stage("Workspace"){
            steps{
                echo "Workspace Path : ${WORKSPACE}"
            }
        }
    }
     post {
        always {
            echo "Final Result is"
        }
        success{
            echo "Success"
        }
        failure {
            echo "Failed!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!"
        }
    }
}
