pipeline{
    agent none
    stages{
        stage('Build'){
            agent{
               label 'maven' 
            } 
            options{
                skipDefaultCheckout()
            }
            steps{
                echo "Hi"
            }
        }
    }
}
