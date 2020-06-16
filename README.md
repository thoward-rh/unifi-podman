# unifi-podman
This is an example service file for running unifi with podman.

I am relying on the docker image ```docker.io/jacobalberty/unifi:latest``` which I have been using for a few years already.

Using latest tag will update each few weeks. You may want to consider adding a script to clear the container if it doesn't shut down cleanly ```#podman rmi unifi``` will do it. 
