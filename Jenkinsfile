pipeline {
    agent any

    

    stages {
        stage('Display Build Info') {
            steps {
                echo "Jenkins URL: ${env.JENKINS_URL}"
                echo "Build ID: ${env.BUILD_ID}"
            }
        }
    }
}
