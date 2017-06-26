node {
    stage "Initialization Process"
        echo "Pipeline Initiated"
    stage "Git Checkout"
        git url: "https://github.com/dineshdinch/PipeLineUsingGIT.git"
    stage "Compiling the Project"
		echo "compilation started"
        bat(returnStdout: true, script: "sh -x -c "pipeline_script.sh").trim()
    stage "Pipeline Process Completed"    
        echo "Pipeline Process Completed"
}