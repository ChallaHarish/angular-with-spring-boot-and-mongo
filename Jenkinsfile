pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh '.mvn/ '
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
