pipeline {
    agent any
    stages {
        stage("deploy") {
            steps {
                echo "deploy stage"
            }
        }
    }
    post {
        always {
            //
            echo "Always execute"
        }
        // success {
        //     echo "Yo~ Success"
        // }
        // failure {
        //     echo "Failed!!!"
        // }
    }
}