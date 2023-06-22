# Docker Getting Started Tutorial

git clone https://github.com/docker/getting-started.git

cd getting-started/app

add below code in Dockerfile
Using a text editor or code editor, add the following contents to the Dockerfile:
   
![image](https://github.com/sateesh5/docker-repo/assets/106376630/2fc36308-b02c-40fa-aecf-aa7c77f3076f)


docker build -t getting-started .

docker run -d -p 3000:3000 getting-started

http://ipaddress:3000/

![image](https://github.com/sateesh5/docker-repo/assets/106376630/1ab3f412-2e52-4e77-9cef-efd7bab2c088)
