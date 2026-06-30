pipeline{
    agent{
         label 'java-agent-slave'
    }
    stages{
        stage('Build'){
            steps{
                echo "Build the maven application"
            }
            stage{
                echo "Scripted pipeline"
                scrpt{
                    def course='k8s'
                    if(course=='k8s'){
                        println("Thanks for enrolling in the $course course")
                        else{
                            println("Please consider learning the $course course")
                        }
                    }
                }
            }
        }
    }
}
