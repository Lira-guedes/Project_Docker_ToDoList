# roda a partir da imagem do node na versão 16 alpine
FROM node:16-alpine

# exponha a porta 3000;
EXPOSE 3000

# defina o diretório de trabalho para /app/front-end
WORKDIR /app/front-end

# adicione o arquivo node_modules.tar.gz à imagem
ADD node_modules.tar.gz .

# copie todos os arquivos da pasta front-end para a imagem. 
COPY . .

#inicie a aplicação com o comando npm start 
ENTRYPOINT [ "npm"]
CMD ["start"]
