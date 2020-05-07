node {

    checkout scm

    docker.withRegistry('https://hub.docker.com/', 'shravyavanne03') {

        def customImage = docker.build("miltonc/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
