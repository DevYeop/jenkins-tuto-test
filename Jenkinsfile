pipeline {
    agent any

    triggers {
        githubPush()
    }

    stages {
        stage('Run CI Script') {
            steps {
                bat 'main.bat'
            }
        }
    }
}
