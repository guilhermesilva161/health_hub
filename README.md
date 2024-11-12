# Chat

Um chatbot simples construído com Node.js que utiliza a biblioteca `whatsapp-web.js` para interagir com o WhatsApp.

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução para JavaScript no lado do servidor.
- **Dependências**:
  - `qrcode-terminal`: Para gerar códigos QR no terminal.
  - `whatsapp-web.js`: Biblioteca para interagir com a API do WhatsApp Web.
  - `mysql2`: Para fazer a conexão e alterações no banco de dados.
  - **MySQL**: Banco de dados.

## Pré-requisitos

Antes de começar, você precisará ter o Node.js instalado em sua máquina. Você pode baixar a versão mais recente do Node.js (Para funcionar precisa ser da versão 18 pra frente.) [aqui](https://nodejs.org/).

## Instalação

1. **Clone o repositório**:"
   ```bash
   git clone https://github.com/seu-usuario/chat.git
   cd chat

2. Instale Dependencias  

npm install whatsapp-web.js

npm install qrcode-terminal

npm install mysql2

## Configuração

3. Configure seu chat 
Abra o arquivo main.js e faça as configurações necessárias conforme a sua necessidade.


## Execução

4.Para executar:
Digite:node main.js

Você verá um código QR no terminal. Escaneie este código com o aplicativo WhatsApp no seu celular.

Uma vez que a conexão for estabelecida, seu chatbot estará pronto para ser utilizado!

## Guia

Guia de como funciona
message.body: são as mensagens do usuário que o chat irá ler para executar a mensagem que ele irá enviar.
message.from: são as mensagens que o chat envia apos ler a mensagem enviada do usuário.

