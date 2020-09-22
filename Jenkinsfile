pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh 'maven-wrapper build '
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
