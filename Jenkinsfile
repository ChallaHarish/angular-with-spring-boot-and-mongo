pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh './mvn/wrapper  build'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
