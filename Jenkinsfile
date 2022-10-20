pipeline {
    agent any
    stages {
        stage('Build1') {
            steps {
                echo 'Running build automation'
                archiveArtifacts artifacts: 'dist/python_test.zip'
            }
        }
    }
}
