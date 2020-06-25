# homehome

$ docker build --tag smp2554/ubuntu3 .
Sending build context to Docker daemon  261.6kB
Step 1/3 : FROM ubuntu
 ---> 74435f89ab78
Step 2/3 : RUN apt update
 ---> Using cache
 ---> 1aff087a320d
Step 3/3 : RUN apt install -y nginx
 ---> Using cache
 ---> d6a0d04c455c
Successfully built d6a0d04c455c
Successfully tagged smp2554/ubuntu3:latest
SECURITY WARNING: You are building a Docker image from Windows against a non-Windows Docker host. All files and directories added to build context will have '-rwxr-xr-x' permissions. It is recommended to double check and reset permissions for sensitive files and directories.
