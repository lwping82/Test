pipeline{
    agent any

    stages{
        stage('checkout'){
            steps{
                sh "git clone https://github.com/lwping82/Test.git"
            }
        }
        stage('build'){
            steps{
                dir("Test") {
                    sh "mvn clean install"
                }
            }
        }
    }
}
