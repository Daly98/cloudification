node {
    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'docker-hub user') {

        def customImage = docker.build("dali98/mohamedali")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
