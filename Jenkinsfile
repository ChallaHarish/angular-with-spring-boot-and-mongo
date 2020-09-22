pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh 'mvn --version'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
