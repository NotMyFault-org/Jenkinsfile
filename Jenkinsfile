pipeline {
    agent any

    stages {
        stage('Build') {
            steps {
                git 'https://github.com/IntellectualSites/PlotSquared/'

                withGradle {
                    sh './gradlew clean build'
                }

            }
        }
    }
}
