# Política de Privacidade — ClipsX

O ClipsX é um aplicativo de uso pessoal, que roda no computador do próprio dono, para gerar
cortes verticais de vídeos e agendar a publicação deles nas contas do próprio usuário.

## Quais dados o ClipsX acessa

- **YouTube (Google):** com a sua autorização, o ClipsX usa os escopos
  `youtube.upload` e `youtube` apenas para enviar os vídeos que você mesmo agendou para o seu
  canal, ler o nome do canal conectado, colocar esses vídeos na playlist escolhida e mudar a data
  de publicação deles. Ele não altera nem apaga outros vídeos, comentários ou dados da sua conta.
- **Instagram:** quando conectado, o acesso é usado apenas para publicar os vídeos que você agendou.
- **TikTok:** com a sua autorização, o ClipsX usa os escopos `user.info.basic` (ler o nome da conta)
  e `video.publish` ou `video.upload` (publicar, ou mandar para os rascunhos, os vídeos que você
  agendou). Ele não lê, altera nem apaga outros vídeos, comentários ou dados da sua conta.

## Onde os dados ficam

- As chaves de acesso, os vídeos, as transcrições e a fila de postagens ficam **somente no
  computador onde o ClipsX está instalado** (pasta `%LOCALAPPDATA%\ClipsX`).
- Nenhum dado é vendido, compartilhado com terceiros ou enviado para servidores do ClipsX — não
  existem servidores do ClipsX.
- A transcrição dos vídeos é enviada à API da Anthropic (Claude) somente para escolher os
  melhores trechos e escrever os textos das postagens.

## Como revogar o acesso

- No ClipsX: tela **Agenda → Desconectar**.
- No Google: <https://myaccount.google.com/permissions>, remova o acesso do app "ClipsX".
- No TikTok: Configurações e privacidade → Segurança → Apps e serviços → remova o "ClipsX".
- Apagar a pasta `%LOCALAPPDATA%\ClipsX` remove todas as chaves e dados locais.

O uso dos dados do YouTube segue os [Termos de Serviço do YouTube](https://www.youtube.com/t/terms)
e a [Política de Privacidade do Google](https://policies.google.com/privacy).

Contato: abra uma issue em <https://github.com/NeriGBR/clipsx-legal/issues>.
