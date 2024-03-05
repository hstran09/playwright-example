pipeline {
    agent any
    tools {
        jdk "OpenJDK 17"
        maven "Maven 3"
    }
    stages {
        stage('Build') {
            steps {
                echo 'Building...'
                echo 'Finished building...'
                sh "mvn exec:java -e -D exec.mainClass=per.hstran09.App -D exec.args=\"install\""
            }
        }
    }
}