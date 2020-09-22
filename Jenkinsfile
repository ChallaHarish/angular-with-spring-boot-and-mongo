pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                echo 'Running build automation'
                sh '.mvn/wrapper/maven-wrapper.properties file'
                archiveArtifacts artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}
