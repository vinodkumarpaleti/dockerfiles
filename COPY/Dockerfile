FROM nginx
RUN rm -rf /usr/share/nginx/html/index.html
# files should be available in current directory where Dockerfile exist
# COPY hello.html /usr/share/nginx/html/hello.html
COPY website/ /usr/share/nginx/html/index.html