pipeline {
    agent any

    stages {
        stage('This is executed for main branches') {
        when {
          branch 'main'
        }
            steps {
                echo 'Hello World'
            }
        }

        stage('This is executed for dev branch') {
        when {
          branch 'develop'
        }
            steps {
                echo 'Hello World'
            }
        }
    }
}
