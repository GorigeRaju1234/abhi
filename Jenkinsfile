node {

    checkout scm

    docker.withRegistry('https://registry.hub.docker.com', 'dockerHub') {

        def customImage = docker.build("sabhishek1107/abhi")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
