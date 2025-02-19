pipeline {
    agent any 

    triggers {
        githubPush {
        }
    }
    stages {
        stage('Build') {
            steps {
                echo "JENKINS_URL: ${env.JENKINS_URL}"
                echo "BUILD_ID: ${env.BUILD_ID}"
            }
        }
    }
}