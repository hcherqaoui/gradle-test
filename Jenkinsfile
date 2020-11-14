pipeline{
    agent any
    tools {
        gradle gradle
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