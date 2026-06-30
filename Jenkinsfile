// comment in jenkins

//any : Executes the pipeline or stage on any available agent. It is the default option if no agent is specified.
//none: when applied at the top level of the pipeline, no global agent will be allowed

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
                script{
                    def course='k8s'
                    if(course=='k8s'){
                        println("Thanks for enrolling in the $course course")
                    }
                        else{
                            println("Please consider learning the $course course")
                        }
                    
                }
            }
        }
    }
}
