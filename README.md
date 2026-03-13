# Chat Missão Bíblico 🙏

Um aplicativo de chat em tempo real que conecta usuários através de conversas sobre a Bíblia. Funciona em celulares e PCs com interface responsiva e acessível!

## 🌟 Características

- ✅ **Chat em Tempo Real**: Mensagens instantâneas entre usuários
- ✅ **Conteúdo Bíblico**: Acesso integrado à Bíblia durante conversas
- ✅ **Responsivo**: Funciona perfeitamente em celulares, tablets e PCs
- ✅ **Acessível**: Design inclusivo para todos os usuários
- ✅ **Backend na Nuvem**: Firebase para armazenamento e autenticação
- ✅ **Multiplataforma**: Web, React Native para mobile

## 🚀 Tecnologias Utilizadas

- **Frontend**: React, Vue.js, HTML/CSS/JavaScript
- **Mobile**: React Native
- **Backend**: Firebase (Firestore + Realtime Database)
- **Autenticação**: Firebase Authentication
- **Hosting**: Firebase Hosting

## 📦 Instalação

### Pré-requisitos
- Node.js v14+ instalado
- npm ou yarn
- Conta Firebase

### Passos

1. Clone o repositório:
```bash
git clone https://github.com/expressodesentope-droid/Chat-miss-o-b-blico-
cd Chat-miss-o-b-blico-
```

2. Instale as dependências:
```bash
npm install
```

3. Configure as variáveis de ambiente (Firebase):
```bash
cp .env.example .env
# Edite o arquivo .env com suas credenciais do Firebase
```

4. Inicie o servidor de desenvolvimento:
```bash
npm start
```

5. Acesse a aplicação em `http://localhost:3000`

## 📱 Estrutura do Projeto

```
Chat-miss-o-b-blico-/
├── public/              # Arquivos públicos
├── src/
│   ├── components/      # Componentes React/Vue
│   ├── pages/          # Páginas da aplicação
│   ├── services/       # Integração Firebase
│   ├── styles/         # CSS responsivo
│   ├── utils/          # Funções auxiliares
│   └── App.js          # Componente principal
├── mobile/             # Código React Native
├── .env.example        # Exemplo de configuração
├── package.json        # Dependências
└── README.md          # Este arquivo
```

## 🛠️ Scripts Disponíveis

```bash
npm start              # Inicia a aplicação em desenvolvimento
npm run build          # Constrói para produção
npm test              # Executa testes
npm run mobile        # Inicia o projeto React Native
```

## 🌐 Implantação

### Deploy no Firebase Hosting

```bash
npm install -g firebase-tools
firebase login
firebase deploy
```

## 🤝 Como Contribuir

1. Faça um fork do repositório
2. Crie uma branch para sua feature (`git checkout -b feature/AmazingFeature`)
3. Commit suas mudanças (`git commit -m 'Add some AmazingFeature'`)
4. Push para a branch (`git push origin feature/AmazingFeature`)
5. Abra um Pull Request

## 📖 Funcionalidades Principais

### 1. Autenticação
- Registro de usuários
- Login/Logout
- Recuperação de senha
- Perfil do usuário

### 2. Chat
- Salas de chat em tempo real
- Histórico de mensagens
- Notificações
- Typing indicator (mostrar quando alguém está digitando)

### 3. Conteúdo Bíblico
- Busca de versículos
- Compartilhamento de trechos bíblicos
- Leitura integrada

### 4. Acessibilidade
- Suporte a leitores de tela
- Contraste de cores adequado
- Navegação por teclado

## 📝 Licença

Este projeto está licenciado sob a Licença MIT - veja o arquivo [LICENSE](LICENSE) para detalhes.

## 👨‍💻 Autor

**expressodesentope-droid**
- GitHub: [@expressodesentope-droid](https://github.com/expressodesentope-droid)

## 💬 Suporte

Para dúvidas ou sugestões, abra uma issue no repositório ou entre em contato.

---

**Feito com ❤️ para a comunidade bíblica!**