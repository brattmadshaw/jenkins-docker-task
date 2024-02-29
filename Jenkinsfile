pipeline {
    agent {
        label "node-worker"
    }
    stages {
        stage("Build Docker Image") {
            steps {
                echo "Building Docker Image..."
                sh docker build -t jenkins1 .
            }
        }
    }
}
