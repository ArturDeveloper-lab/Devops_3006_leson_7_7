properties([pipelineTriggers([pollSCM('*/30 * * * *')])])
node {
    stage("close"){
        git "https://github.com/arturolga/Devops_3006_leson_7_7.git"
    }
    stage("show files"){
        sh "ls -l"
    }
}
