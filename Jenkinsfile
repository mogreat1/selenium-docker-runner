pipeline{
	agent any
	stages{
		stage("Run Test"){
			bat "docker-compose up"
		}
	}
		stage("Bring Grid Down"){
			bat "docker-compose down"
		}
	}
}