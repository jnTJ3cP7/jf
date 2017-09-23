pipeline {
    agent any
    stages {
        stage("Checkout") {
            steps {
                git url: 'https://github.com/jnTJ3cP7/g-j-test.git'
            }
        }
        stage("Compile") {
            steps {
                sh "./gradlew classes --stacktrace"
            }
        }
    }
}