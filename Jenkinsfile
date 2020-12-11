node {
    checkout scm
    bat 'docker ps -a'
    bat 'docker start c5569465caa0'
    bat 'docker run -p 49160:8080 -d bharathjg/dockerwebapp'
    bat 'curl localhost:49160'
}
