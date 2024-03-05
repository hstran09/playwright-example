pipeline {
    agent any
    stages {
        stage('Build') {
            steps {
                script {
                    echo 'Building...'
                    echo 'Finished building...'
                    sh "mvn exec:java -e -D exec.mainClass=per.hstran09.App -D exec.args=\"install\""
                }
            }
        }
    }
}