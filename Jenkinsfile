pipeline {
    agent any
    stages {
        stage("run frontend") {
            steps {
                echo "yarn executing..."
                nodejs("node-14-15") {
                    sh "yarn install"
                }
            }
        }
    }
}