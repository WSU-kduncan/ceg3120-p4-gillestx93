# Run project locally
- Once I installed Docker on my desktop
- To build a new container for my project I ran the command `docker create --name nginx_base -p 80:80 nginx:alpine`
- I ran the container by using the command `docker start nginx_base`
- From here, I copied the index.html file into the docker container by using the command `docker cp html/index.html nginx_base:/usr/share/nginx/html/index.html`
- In order to view my project I go to my localhost.
