pipeline {
    agent any
    tools {
        Terraform 'Terraform v0.12.12'
    }
    stages {
        stage('Example') {
            steps {
                sh 'terraform --version'
            }
        }
    }
}
