pipeline {
    agent any
    stages {
        stage ('Set Terraform path') {
            steps {
                echo 'Hello World'
                script {
                    env.PATH += ":/usr/local/bin/" 
                    ansiColor('xterm') {
                        sh 'terraform --version'
                    }
                }
            }
        } 
    }
}
