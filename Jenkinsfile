pipeline {
    agent {label "arnabsasas"}
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                archiveArtifacts artifacts: 'dist/python_test.zip'
            }
        }
    }
}
