FROM nginx:1.30.6-alpine
RUN rm -rf /usr/share/nginx/html/*
COPY site/ /usr/share/nginx/html/
EXPOSE 80
LABEL org.opencontainers.image.authors="DanilovD"
LABEL org.opencontainers.image.description="Учебный образ nginx со статической страницей"
WORKDIR /usr/share/nginx/html
