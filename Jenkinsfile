pipeline{
    agent any
    stages {
        stage("Checkout"){
            steps{
                git url: 'https://github.com/jcy16/calculator.git', branch:'main'
            }
        }
        stage("Compile"){
            steps{
            sh "./gradlew compileJava"
            }
        }
    }
}
