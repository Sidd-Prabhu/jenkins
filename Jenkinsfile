pipeline{
    agent any
    parameters{
        booleanParam(defaultValue: false, description: "Enable sevice?", name: "myBoolean")
    }
    stages{
        stage("Demo"){
            steps{
                echo "booleanParam is set to: ${params.myBoolean}"
            }
        }
    }
}
