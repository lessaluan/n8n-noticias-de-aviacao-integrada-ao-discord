# Notícias de Aviação Integrada ao Discord

## Sobre o projeto
Utilizando o n8n este projeto integra um site de notícias sobre aviação (AeroFlap) e o aplicativo Discord.
A cada duas horas o gatilho inicial (RSS TRIGGER) busca no site AeroFlap a notícia mais recente e envia (Send Message) para o canal no Discord #noticias-aviação-n8n.

## Funcionalidades
- Buscar dados/notícias a partir de sites na web.
- Enviar para o canal do Discord

## Visualização:

## Workflow do n8n:

![Captura de Tela do n8n - Workflow](screenshots/n8n-workflow-noticiasaviacao.png)

## Mensagem recebida no Discord:

![Captura de Tela do Discord - Mensagem recebida](screenshots/n8n-discord-noticiasaviacao.png)


## Pré-requisitos
- n8n hospedado, podendo ser em uma VPS ou localmente.
- Conta no Discord.

## Autor
Luan Lessa

Data: 09/11/2025
