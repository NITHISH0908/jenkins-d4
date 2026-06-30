pipeline{
    agent any
    stages{
        stage('BUild'){
            steps{
                echo 'Entering the build block'
                retry(3){
                    echo "welocome to D4"
                    error 'Build is getting failed'
                }
                echo 'Build Successfully completed.'
            }
        }
    }
}
