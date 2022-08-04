#define a imagem base
FROM node:16.16.0
#define um diretorio de trabalho
WORKDIR /app
#copia os arquivos do package e package-loc.json
COPY ./package*.json ./
#instala as dependecias do projeto
RUN npm install
#copia o restos dos arquivos
COPY . .
#expoem a porta 8080
EXPOSE 8080
#inicia a aplicação
CMD ["node", "server.js"]

