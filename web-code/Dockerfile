FROM node:18-buster-slim
RUN npm install -g http-server
ADD index.html index.html
EXPOSE 80
CMD ["npx", "http-server"]