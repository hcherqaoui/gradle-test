pipeline{
    agent any
    tools {
        gradle
    }
    stages {
        stage("bluid"){
        steps {
            echo 'Building application ...'
            sh "gradle bootJar"
        }
        }
    }
}