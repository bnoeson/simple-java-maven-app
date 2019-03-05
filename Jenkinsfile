pipeline{
    agent { label 'my-defined-label' }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B clean install'
            }
        }
    }
}