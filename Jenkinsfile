pipeline {
    agent any
    tools {
        Terraform 'terraform 0.12.12'
    }
    stages {
        stage('Example') {
            steps {
                sh 'terraform --version'
            }
        }
    }
}
