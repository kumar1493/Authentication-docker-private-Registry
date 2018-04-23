# Authentication-docker-private-Registry
Using Authentication to provide credentials to onpremise server to login from different servers to push or pull images.This yaml code is used for if you have load balancer insatlled in your onpremise.

other wise when you try to login 
docker login 10.xx.xx.xx:5000
username: docker
pwd: docker

you get this error
Error response from daemon: Get https://10.xx.xx.xx:5000/v2/: dial tcp 10.xx.xx.xx:5000: getsockopt: connection refused
