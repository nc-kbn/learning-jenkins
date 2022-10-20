pipeline {
    agent any

    options([
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