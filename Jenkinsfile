pipeline {
    agent {
        node {
            label 'built-in' // Use Jenkins' built-in node
        }
    }
    
    stages {
        stage('Build') {
            steps {
                echo 'Hello, World!'
            }
        }
    }
    
    post {
        always {
            echo 'Post-build action executed!'
        }
        success {
            echo 'Build was a success!'
        }
        failure {
            echo 'Build failed!'
        }
    }
}
