pipeline{
    agent any
    stages{
        stage("Demo"){
            steps{
               myFunc("World")
            }
        }
    }
}
def myFunc(String myText)
{
    echo "Hello ${myText}"
}
