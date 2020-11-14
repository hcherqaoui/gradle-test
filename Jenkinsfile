pipeline{
    agent any
    stages {
        stage("bluid"){
        steps {
            echo 'Building application ...'
            sh "gradle bootJar"
        }
        }
    }
}