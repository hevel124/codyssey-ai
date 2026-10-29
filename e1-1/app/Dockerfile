FROM nginx:alpine
LABEL description="e1-1 custom nginx"
COPY site/ /usr/share/nginx/html/
HEALTHCHECK --interval=10s CMD wget -q -O /dev/null http://localhost/ || exit 1
