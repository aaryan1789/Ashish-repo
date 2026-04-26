pipeline {
agent any

stages {
    stage('Build') {
        steps {
            echo 'Starting build process...'
        }
    }

    stage('Test') {
        steps {
            echo 'Running tests...'
        }
    }

    stage('Deploy') {
        steps {
            echo 'Deploying application...'
        }
    }
}

post {
    always {
        echo 'Pipeline execution completed.'
    }
    success {
        echo 'Pipeline succeeded!'
    }
    failure {
        echo 'Pipeline failed!'
    }
}


}
