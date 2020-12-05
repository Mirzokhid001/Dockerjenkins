node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/r/mirzokhid001/dockerwebapp', 'dockerhub') {

        def customImage = docker.build("mirzokhid001/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
