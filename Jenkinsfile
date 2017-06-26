node {
    stage "Initialization Process"
        echo "Pipeline Initiated"
    stage "Git Checkout"
        git url: "https://github.com/dineshdinch/PipeLineUsingGIT.git"
    stage "Compiling the Project"
		echo "compilation started"
        bat "sh pipeline_script.sh"
    stage "Pipeline Process Completed"    
        echo "Pipeline Process Completed"
}