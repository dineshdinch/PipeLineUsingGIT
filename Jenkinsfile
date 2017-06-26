node {
    stage "Initialization Process"
        echo "Pipeline Initiated"
    stage "Git Checkout"
        git url: "https://github.com/dineshdinch/PipelineGIT.git"
    stage "Compiling the Project"
        sh "build.sh"
    stage "Pipeline Process Completed"    
        echo "Pipeline Process Completed"
}