FROM nginx

# Копирует файлы из указанной директории в указанную директорию
COPY . /usr/share/nginx/html

# Запускает контейнер
CMD ["nginx-debug", "-g", "daemon off;"]
