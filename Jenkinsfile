pipeline {
    agent any

    stages {
        stage('Hello') {
            steps {
                echo "Branch: {params.branch}"
                echo "Repository: {params.repo}"
            }
        }
    }
}
