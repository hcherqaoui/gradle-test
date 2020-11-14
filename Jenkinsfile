pipeline{
    agent any

    stages {
        stage("bluid"){
        steps {
            echo 'Building application ...'
            sh "./gradlew clean test bootJar"
        }
        }
    }
}