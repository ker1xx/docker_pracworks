# Используем базовый образ Nginx
FROM nginx:latest
WORKDIR /usr/share/nginx/html

# Копируем HTML-страницы
COPY . /usr/share/nginx/html

EXPOSE 80

# Nginx автоматически обслуживает содержимое этой папки