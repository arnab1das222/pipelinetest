pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                archiveArtifacts artifacts: 'dist/python_test.zip'
            }
        }
    }
}
