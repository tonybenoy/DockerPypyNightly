# Dockerfile with pypy nightly builds </br>
Docker image based on buster with pypy(nightly) based of the official pypy images </br>
Get nightly link from http://buildbot.pypy.org/nightly/trunk/
# Build image </br>
> docker build . -t pypy-nightly

# Build image </br>
> docker run -it pypy-nightly
