pipeline{
    agent any
    parameters{
        string(defaultValue: '', description: "Which choice?", name: "choiceParam")
        choice(choices: ["EU-WEST-2A", "EU-WEST-2B", "EU-WEST-2C"], description: "Which AZ to deploy?", name: "deployEnv")
        booleanParam(defaultValue: false, description: "Confirm?", name: "confirmParam")
    }
    stages{
        stage("Choice"){
            steps{
                echo "String is as: ${choiceParam}\n"
                echo "Choice is set as: ${deployEnv}\n"
                echo "Bool is set as: ${confirmParam}"
            }
        }
    }
}
