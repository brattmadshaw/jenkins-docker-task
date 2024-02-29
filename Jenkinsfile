pipeline {
    agent {
        label "abc"
    }
    stages {
        stage("make directory") {
            steps {
                sh "mkdir ~/jenkins-pipelines || true"
            }
        }
    }
}
