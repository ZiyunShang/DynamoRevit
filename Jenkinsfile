stage ('Starting DynamoRevit build job') {
    def branchToBuild = env.BRANCH_NAME
    build job: '../DynamoRevitUtils/RC2.3.0_Revit2020', parameters: [[$class: 'StringParameterValue', name: 'BranchDynamoRevit', value: branchToBuild ]]
}
