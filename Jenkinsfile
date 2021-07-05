pipeline {
    agent {
        docker {
            image 'broadinstitute/scala-baseimage'
        }
    }
    stages {
        stage('Test') {
            steps {
                echo 'Building..'
                sh "sbt test"
            }
        }
    } 
}
