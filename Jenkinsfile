pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh '.mvn/wrapper'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
