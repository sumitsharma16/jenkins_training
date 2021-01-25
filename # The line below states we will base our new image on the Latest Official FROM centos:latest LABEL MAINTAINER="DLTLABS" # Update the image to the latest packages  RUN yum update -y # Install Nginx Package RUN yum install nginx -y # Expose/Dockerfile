# The line below states we will base our new image on the Latest Official
FROM centos:latest
LABEL MAINTAINER="DLTLABS"
# Update the image to the latest packages 
RUN yum update -y
# Install Nginx Package
RUN yum install nginx -y
# Expose/Open port 80
EXPOSE 80
# Last is the actual command to start up NGINX within our Container
CMD ["nginx", "-g", "daemon off;"]
