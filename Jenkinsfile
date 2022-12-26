
pipeline {
// single line    
    agent any
    stages {
        stage('Git checkout') {
            steps {
                echo "checking out"
                checkout([$class: 'GitSCM', branches: [[name: '*/master']], extensions: [], userRemoteConfigs: [[url: 'https://github.com/Strvsuri/Mr.devopsvikash-kumar01-Kubernetes_Project']]])
            }
        }
    }
}
