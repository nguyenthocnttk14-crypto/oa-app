# Dùng image Nginx bản nhẹ (alpine) để serve file tĩnh
FROM nginx:alpine

# Xóa file mặc định của Nginx
RUN rm -rf /usr/share/nginx/html/*

# Copy toàn bộ file HTML/CSS trong thư mục hiện tại vào thư mục Nginx serve
COPY . /usr/share/nginx/html/

# Nginx mặc định lắng nghe port 80
EXPOSE 80
