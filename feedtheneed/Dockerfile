FROM node:16
WORKDIR /app

COPY . /app
RUN npm install

ENV VITE_API_URL=http://localhost:4000/api/v1/
ENV VITE_FRONTEND=http://localhost:3000
ENV VITE_GOOGLE_MAPS=AIzaSyD_59ZJjJjQGGchrL0-6kckYczHH846egw

CMD [ "npm", "dev" ]
EXPOSE 3000
