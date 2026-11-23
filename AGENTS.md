# AGENTS.md — rclone-youtube

> **Leia antes `../AGENTS.md`**, na raiz do workspace.

- Este repositório é **público** e serve o site do app do Google pelo GitHub Pages (`index.html`, `privacidade.html`, `youtube/`). É o endereço que a tela de consentimento OAuth mostra.
- **Nunca entra segredo aqui**: nada de `client_secret*.json`, token, chave ou `.env`, nem "só por um commit". As credenciais ficam em `~/.config/youtube-channel/` e no `.env` do kit.
- Mudança de texto da página de privacidade ou da página inicial muda o que o Google revisou: avise o Collins antes.
