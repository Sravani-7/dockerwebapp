node {
    checkout scm

    docker.withRegistry('https://github.com/Sravani-7/dockerwebapp.git', 'dockerhub') {

        def customImage = docker.build(madhavi/dockerwebapp")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
