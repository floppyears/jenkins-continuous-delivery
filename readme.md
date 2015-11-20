# Jenkins Continuous Delivery

This repository contains the Jenkins configuration for automatically generating continuous integration and continuous delivery jobs for [Web APIs](https://github.com/osu-mist/web-api-skeleton) built with Dropwizard and Gradle.


## Run

Define environment variables and execute Jenkins:

    $ export JENKINS_HOME=/path/to/jenkins-continuous-delivery
    $ export API_HOST_NAME=sub.domain.oregonstate.edu
    $ export API_HOST_USER=janedoe
    $ export API_HOST_KEY=/path/to/.ssh/id_rsa
    $ java -jar ../jenkins.war &> /dev/null &
