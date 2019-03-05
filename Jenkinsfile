pipeline{
    agent none
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B clean install'
            }
        }
    }
}