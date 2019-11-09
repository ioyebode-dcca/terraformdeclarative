pipeline {
    agent any
    stages {
        stage ('Set Terraform path') {
            steps {
                echo 'Hello World'
                script {
                    def tfHome = tool name: 'Terraform'
                    env.PATH = "${tfHome}:${env.PATH}" {
                        sh 'terraform — version'
                    }
                }
            }
        } 
    }
}
