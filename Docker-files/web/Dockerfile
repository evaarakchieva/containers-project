FROM nginx
LABEL "Project"="vprofile"
LABEL "Author"="Eva"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginxvproapp.conf /etc/nginx/conf.d/vproapp.conf