node {

    stage('Clone Repository')
    {
        checkout scm
    }

    stage('Show me the files') {

        sh "ls -l"	
       
    }
    stage('Apply changes to the environment') {
        
        sh"ls -l"
        sh "php -s local host:5000"
    }
    
}
