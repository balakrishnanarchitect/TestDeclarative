pipeline{
    agent any
    stages{
        stage("compile"){
            steps{
                echo "this will compile the code"
            }
        }
        stage("build"){
            steps{
                echo "this will build  the code"
            }
        }
        stage("test"){
            steps{
                echo "this will compile the code"
            }
        }
        stage("release"){
            steps{
                echo "this will release the code"
            }
        }
    }
    
}
