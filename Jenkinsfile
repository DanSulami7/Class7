properties([pipelineTriggers([pollSCM('* * * * *')])])

node("Dan"){
    stage("clone"){
        git branch: 'main', url: 'https://github.com/DanSulami7/Class7.git'

    }
    stage("execute"){
        bat "dir"
        bat "python main.py"
    }
}