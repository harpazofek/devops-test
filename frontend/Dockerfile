FROM node:18.13.0

RUN npm install -g serve
RUN apt-get update && apt install -y xsel

WORKDIR /app

COPY . .

EXPOSE 8080
ENV PORT 8080
CMD [ "serve", "-s" ]