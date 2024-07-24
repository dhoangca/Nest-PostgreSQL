# Vesion Node.js
FROM node:20

# Tạo thư mục làm việc
WORKDIR /usr/src/app

# Port của ứng dụng
EXPOSE 3000

# Copy package.json và package-lock.json
COPY ../package.json ../package-lock.json ./

# Cài đặt các dependencies
RUN npm install

COPY ../ ./

CMD ["npm", "start"]