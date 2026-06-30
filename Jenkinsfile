// we use tools section to auto=install packages or define path of the package
// we can add tools sectioon under pipeline > stages > stage >tools

//

//pipeline > tools

  pipeline{
    agent any
    tools{
        maven 'MAVEN_PATH'
    }
    stages{
        stage('Maven'){
            steps{
            echo "Maven Version"
            sh 'mvn -version'
            }
        }
        stage('specific stage'){
            tools{
                jdk 'JDK-17'
            }
             steps{
                echo "execuyting Tools under stage area"
                sh 'mvn -version'
             }
        }
    }
  }        
