# roda a partir da imagem do node na versão 16 alpine
FROM node:16-alpine

# exponha a porta 3001;
EXPOSE 3001

# defina o diretório de trabalho para /app/back-end
WORKDIR /app/back-end

# adicione o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz .

# copie todos os arquivos da pasta back-end para a imagem. 
COPY . .

#inicie a aplicação com o comando npm start 
ENTRYPOINT [ "npm"]
CMD ["start"]
