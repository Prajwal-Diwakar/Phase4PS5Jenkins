pipeline {

	agent any
	
	triggers {
		pollSCM('* * * * *')
	}
	
	stages {

		
		stage('Compile stage') {
			steps {
				echo '--------------:: This is a compile stage :: ------------'
				bat 'mvn clean compile'
			}
	
		}
		
		stage('Test stage') {
			steps {
				echo '--------------:: This is a compile stage :: ------------'
				bat 'mvn clean test'
			}
			
            
	
		}
		
	}

}