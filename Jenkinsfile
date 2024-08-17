pipeline{
    agent any
    stages{
        stage("Build"){
            steps {
                echo "======== Executing Build ========"
            }
            post {
                always{
                    echo "======== Done ========"
                }
            }
        }
    }

}