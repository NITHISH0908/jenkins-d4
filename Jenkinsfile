pipeline{
    agent any
    stages{
        stage('Build'){
            steps{
                echo "Entering into timeout block"
                timeout(time: 5, unit: 'SECONDS'){
                    echo "welcome home"
                    sleep 60
                }

            }
        }
    }
}
