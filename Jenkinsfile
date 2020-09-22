pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './mvnw build'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
