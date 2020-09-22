pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh 'mvn -N io.takari:maven:wrapper'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
