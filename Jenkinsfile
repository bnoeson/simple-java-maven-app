pipeline{
    agent { label 'Jenkins' }
    stages {
        stage('Build') {
            steps {
                sh 'mvn -B clean install'
            }
        }
    }
}