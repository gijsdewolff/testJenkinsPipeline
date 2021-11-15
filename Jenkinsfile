pipeline {
    agent windows-agent
    stages {
        stage('Build') { 
            steps {              
                dir("build_folder"){
                    bat "run_build_windows.bat"
                }   
            }
        }
    }
}
