# !bin/bash -il
node -v
npm install
npm run build
ls -la
docker stop nginx
docker rm nginx
docker run -itd --name nginx -v /volume1/docker/jenkins/workspace/vuedemo/dist:/usr/share/nginx/html -p 9001:80 nginx