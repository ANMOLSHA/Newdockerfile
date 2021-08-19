node{
	checkout scm
	docker.withRegistry("https://registry.hub.docker.com","Dockerhub"){
	def customImage = docker.build("sunidhi132000/dockerpipeline")
	customImage.push()

  }
}
