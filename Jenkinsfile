pipeline {
    agent any

    properties([
    pipelineTriggers([cron('* * * * *')])
])

    stages {
        stage('Stage 1') {
            steps {
                echo 'Building..'
            }
        }
        
    }
}