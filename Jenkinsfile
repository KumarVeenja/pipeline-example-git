pipeline{
	agent any
	stages{
		stage("compile"){
			steps{
				bat 'javac Test.java'
			}
			
		}
		stage("run"){
			steps{
				bat "java Test"
			}
		}
	}
	
	post{
		always{
			echo "always"
		}

		success{
			echo "success"
		}

		failure{
			echo "failure"
		}


		

	}


}