pipeline{
    agent any
    parameters{
        booleanParam(defaultValue: false, description: "Select your namespace", name: "namespace")
    }
    stages{
        stage("Demo"){
            steps{
                script{
                    if(params.namespace== false)
                    {
                       echo "Your namespace is other............."
                    }
                    else
                    {
                        echo "Namespace is set as ${params.namespace}"
                    }
                }
            }
        }
    }
}
