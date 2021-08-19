node{
	checkout scm
	docker.withRegistry("https://registry.hub.docker.com","dockerHub"){
	def customImage = docker.build("sunidhi132000/dockerpipeline")
	customImage.push()

  }
}
