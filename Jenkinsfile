node{
    git branch:'main', url: 'https://github.com/mostafaAli-17/K8s_project2.git'
    stage('bulid'){
    try{
            sh'echo "bulid stage"'
    }
    catch(Excption e){
        sh'echo "exception found"'
        throw e
       }
    }
    stage('test'){
        if(env.BRANCH_NAME == "faet"){
            sh'echo "test stage"'
        }
        else{
            sh'echo "skip test stage"'
        }
    }
}
