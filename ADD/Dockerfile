from almalinux:9
run dnf install nginx -y
run rm -rf /usr/share/nginx/html/index.html
add https://raw.githubusercontent.com/SumanthKumarTirumalasetti/dockerfiles/refs/heads/main/RUN/Dockerfile /usr/share/nginx/html/index.html
run chmod +r /usr/share/nginx/html/index.html
cmd ["nginx" , "-g" , "daemon off;"]