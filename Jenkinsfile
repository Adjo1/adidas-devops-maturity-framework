pipeline{
    agent any

    stages{
        stage('initialization'){
            steps{
                echo 'initialisation'
                sh 'docker --version'
            }
        }
        stage('building'){
            steps{
                echo 'building'
                sh 'docker build -t test:${BUILD_ID} .'
            }
        }
        
        stage ('deploy'){
            steps{
                echo 'deploying'
            }
        }
    
    }
}
