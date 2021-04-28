# Run project locally
- Once I installed Docker on my desktop
- To build a new container for my project I ran the command `docker create --name nginx_base -p 80:80 nginx:alpine`
- I ran the container by using the command `docker start nginx_base`
- From here, I copied the index.html file into the docker container by using the command `docker cp html/index.html nginx_base:/usr/share/nginx/html/index.html`
- In order to view my project I go to my localhost.

# Configure AWS CLI
- To install AWS CLI I ran the code `docker run --rm -it amazon/aws-cli' in my WSL2 instance 
- To configure the AWS CLI I followed the steps listed on the AWS website: https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2-docker.html

# DockerHub Repositories
- To create the repository I signed into DockerHub, chose the Repositories tab and then selected Create Repository.
- 
