pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './mavenw build'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
