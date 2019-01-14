pipeline {
    agent {
        docker {
            image "ruby"
            args "--selenium"
        }
    }
    stages {
        stage("Build") {
            steps {
                sh "bundle install"
                sh "cucumber"
            }
        }
    }
}
