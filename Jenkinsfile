pipeline {
    agent any
    
    stages {
        stage('Build') {
            steps {
                script {
                    // Echo the Build Number
                    echo "Build_Number: ${BUILD_NUMBER}"

                    // List files in the workspace
                    sh 'ls'
                }
            }
        }
    }
}
