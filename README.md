# WebChat

Um chat em tempo real usando WebSocket e Protocol Buffers.

![WebChat Screenshot](screenshot.png)

## 📋 Descrição

WebChat é uma aplicação de bate-papo em tempo real que utiliza WebSockets para comunicação instantânea entre usuários. O projeto implementa Protocol Buffers (Protobuf) para serialização eficiente de dados, garantindo uma transmissão rápida e econômica de mensagens.

## ✨ Funcionalidades

- Comunicação real-time via WebSockets
- Interface de usuário simples e intuitiva
- Registro de usuários com armazenamento em Protocol Buffers
- Timestamp nas mensagens
- Notificações de entrada e saída de usuários

## 🔧 Tecnologias Utilizadas

- WebSocket API
  
- **Backend**:
  - Node.js
  - WebSocket (ws)
  - Protocol Buffers (protobufjs)
  - File System para persistência de dados

- **Frontend**:
  - HTML5
  - CSS3
  - JavaScript 

## 🚀 Como Executar

### Pré-requisitos

- Node.js (versão 14.x ou superior)
- npm (normalmente instalado com o Node.js)

### Instalação

1. Clone o repositório:
   ```bash
   git clone https://github.com/laviniaaaf/webchat.git
   cd webchat
   ```

2. Instale as dependências:
   ```bash
   npm install
   ```

3. Inicie o servidor:
   ```bash
   npm start
   ```

4. Abra o arquivo `index.html` em seu navegador ou use um servidor HTTP simples:

## 📝 Como Usar

1. Ao acessar a aplicação, você será solicitado a digitar seu nome
2. Após registrar seu nome, você poderá enviar mensagens que serão vistas por todos os usuários conectados
3. As mensagens aparecem com timestamp e nome do remetente
4. Para sair, basta fechar a janela do navegador



