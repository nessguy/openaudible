pipeline { 
    agent any 
    options {
        skipStagesAfterUnstable()
    }
    stages {
        
        stage('Clean') { 
            steps { 
                mvn clean 
            }
        }
        stage('Build') { 
            steps { 
                mvn install
            }
        }        
    }
}
