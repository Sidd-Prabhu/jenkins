pipeline{
    agent any
    environment{
        def myString = "Hello World"
        def myNumber = 10
        def myBool = false
    }
    stages{
        stage("Demo"){
            steps{
                echo "myString is ${myString}\n"
                echo "myString is ${myNumber}\n"
                echo "myString is ${myBool}"
            }
        }
    }
}
