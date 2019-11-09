pipeline {
    agent any
    tools {
        terraform 'Terraform-0.12.12'
    }
    stages {
        stage('Example') {
            steps {
                sh 'terraform --version'
            }
        }
    }
}
