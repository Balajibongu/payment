@Library('jenkins-shared-library') _

def configMap= [
    projectname : "roboshop",
    directory : "payment"
]

// echo "now we are executing the payment"
echo "now we are executing the payment in feature_branch"

if( env.BRANCH_NAME.equalsIgnoreCase("main") ){
    echo "please folow the RP"
}
else{
    PythonJenkins(configMap)
}