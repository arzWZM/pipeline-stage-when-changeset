pipeline {
    agent any
	
    stages {
        stage('Build') {
		
			when{
				changeset glob: "*.js"
			}
		
            steps {                
                echo 'Hello World changeset JS'
            }
        }
    }
}
