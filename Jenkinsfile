/*
pipeline {
    agent any
    stages {
        stage("Main Branch") {
            when {
                branch "main"
            }
            steps {
                echo "Integrated into Main Branch"
            }
        }
        stage("DEV Branch") {
            when {
                branch "Dev"
            }
            steps {
                echo "Integrated in DEV Branch"
            }
        }
    }
}
*/

pipeline {
    agent none
    stages {
        stage('SkipDefaultCheckout checking........') {
            agent any
            /*options {
                skipDefaultCheckout()
            */}
            steps {
                echo "Hello Narendra"
            }
        }
    }
}
        
