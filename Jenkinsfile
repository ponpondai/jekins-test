pipeline {​
    agent { label 'master' }​
    stages {​
        stage('hello') {​
            steps {​
                script{
                    jenkins = Jenkins.instance
                    import jenkins.model.*
                }
            }​
        }
        stage('world') {
            steps {
                sh "ls -al"
            }
        }
    }​
}​