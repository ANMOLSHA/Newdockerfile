node{
	checkout scm
	docker.withRegistry("https://registry.hub.docker.com","Dockerhub"){
	def customImage = docker.build("anmolsharma02/dockerpipeline")
	customImage.push()

  }
}
