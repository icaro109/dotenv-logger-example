FROM node:18-alpine

# Diretório da aplicação
WORKDIR /app

# Copie os arquivos do package.json e package-lock.json
COPY package*.json ./

# Instale as dependências
RUN npm install

# Copie o restante da aplicação
COPY . .

# Porta exposta
EXPOSE 3000

# Comando padrão
CMD ["npm", "start"]
