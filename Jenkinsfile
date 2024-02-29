pipeline{
    agent {
        label "test-pipeline"
    }
    stages{
        stage("make directory"){
            steps{
              sh echo "Building Docker Image..."
              sh 'docker build -t jenkins1 .'
            }
        }
    }
}
