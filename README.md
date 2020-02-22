# Very Useful Tools to Remember

Instruções para executar o projeto

## Instalar e configurar o projeto

### Instalação das dependências

Dentro da pasta do projeto utilize `npm install` para instalar as dependências.

### Configurar o Banco de Dados

Esse projeto utilizou um Banco de Dados MongoDB hospedado na plataforma [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
Após obter sua url de conexão no MongoDB Atlas insira no arquivo `connection.js` que se encontra em:
> /src/config/connection.js
A sua URL de conexão fornecida pelo MongoDB Atlas conforme no exemplo de código abaixo:
```javascript
const URL = 'mongodb+srv://user:password@vuttr-evkan.mongodb.net/data_base';
```

## Executar o projeto

Os scripts disponíveis para executar o projeto a partir de seu diretório são os seguintes:

### `npm start`

Utilize `npm start` para executar o projeto com o servidor do node.
A porta onde a API estará sendo executada é a 3000.

### `npm run-script dev`

Utilize `npm run-script dev` para executar o projeto em modo de desenvolvimento com o servidor do [nodemon](https://nodemon.io/).
Essa ferramenta permite que o servidor seja recarregado automaticamente após as modificações no código do projeto serem salvas.
