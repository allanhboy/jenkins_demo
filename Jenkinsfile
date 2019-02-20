node{
    checkout scm

    def customImage = docker.build("jenkins_demo:${env.BUILD_ID}")

    customImage.push()
}