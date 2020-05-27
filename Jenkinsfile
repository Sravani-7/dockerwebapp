node {
    checkout scm

    docker.withRegistry('https://github.com/Sravani-7/dockerwebapp.git', 'dockerhub') {

        def customImage = docker.build("madhavi/node-web-app")

        /* Push the container to the custom Registry */
        customImage.push()
    }
}
