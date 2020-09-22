pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh 'mvn clean install'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
