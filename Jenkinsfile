pipeline {
    agent any
    stages {
        stage('Build') {
            setps {
                echo "Running build automation"
                sh './gradlew build --no-daemon'
                archivePath artifacts: 'dist/trainSchedule.zip'
            }
        }
    }
}