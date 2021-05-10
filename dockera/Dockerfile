FROM alpine 
RUN apk add --update nodejs nodejs-npm
RUN npm install -g http-server
COPY . /var/www/java  
WORKDIR /var/www/java  
EXPOSE 8099
ENTRYPOINT ["http-server","-p","8099"]

