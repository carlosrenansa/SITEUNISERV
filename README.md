# Site de Vendas UNISERV

Landing page de vendas do sistema UNISERV, inspirada nos sites de [Trello](https://trello.com/pt-BR), [Monday.com](https://monday.com), [ClickUp](https://clickup.com), [Notion](https://www.notion.com) e [Jira](https://www.atlassian.com/software/jira).

## Conteúdo (inspirado em Trello, Monday, ClickUp, Notion, Jira)

- **Hero** – Logo, título de impacto e CTA
- **Quem confia** – Placeholder para logos de clientes
- **Pain point** – Frase de impacto sobre problemas com planilhas/sistemas separados
- **Stats** – Números (9+ módulos, 100% em PT, etc.)
- **Use case picker** – Chips "O que você gostaria de gerenciar?"
- **Formulário de leads** – Nome, e-mail, telefone, empresa, interesse
- **Tabela de comparação** – UNISERV vs Planilhas vs Sistemas separados
- **Funcionalidades** – Grid de módulos
- **Soluções** – Por área/equipe
- **Como funciona** – 3 passos (formulário → demo → começar)
- **Diferenciais** – Integração, implementação rápida, 100% brasileiro
- **Vídeo** – Placeholder para demonstração (trocar por iframe do YouTube)
- **Depoimentos** – 3 cards
- **FAQ** – Perguntas frequentes em accordion
- **CTA final** – Formulário ou WhatsApp
- **Trust badges** – Demonstração grátis, suporte PT, etc.
- **Footer expandido** – Links organizados
- **Menu mobile** – Hamburger em telas pequenas
- **Animações** – Fade-in ao rolar
- **Botão flutuante** – WhatsApp sempre visível

## Contato configurado

- **WhatsApp:** (91) 99186-3535
- **E-mail:** rlconsultoriaexecutiva@gmail.com

## Formulário de leads

O formulário usa o [FormSubmit](https://formsubmit.co/) (gratuito). Os dados são enviados para o seu e-mail.

**Primeira vez:** ao enviar o primeiro formulário, o FormSubmit manda um e-mail de ativação para `rlconsultoriaexecutiva@gmail.com`. É preciso clicar no link para ativar. Depois disso, todos os envios passam a chegar normalmente.

Após o envio, o visitante é redirecionado para `obrigado.html`, com um botão para abrir o WhatsApp.

## Como visualizar

1. Abra `index.html` no navegador (duplo clique no arquivo)
2. Ou use um servidor local: `python3 -m http.server 8080` na pasta do projeto e acesse `http://localhost:8080`

## Hospedagem

O site é estático. Pode ser publicado em:

- GitHub Pages
- Netlify
- Vercel
- Qualquer servidor de arquivos estáticos

Se o site ficar em um subdiretório (ex: `seusite.com/uniserv/`), ajuste o valor de `_next` no formulário para o caminho correto da página de obrigado (ex: `obrigado.html` ou `https://seusite.com/uniserv/obrigado.html`).
