pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Branch: ${params.BRANCH}"
                echo "Repository: ${params.REPO}"
            }
        }
    }
}
