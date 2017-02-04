# jenkins-ssh-slave-ruby
docker jenkins ssh slave for ruby

based on jenkinsci/ssh-slave

## BUILD
    docker build -t jenkins-ssh-slave-ruby .

## RUN
    docker run -d jenkins-ssh-slave-ruby "<public key>"
