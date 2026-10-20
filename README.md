# Pedagogia Gamificada

Página de apresentação dos aplicativos educacionais com jogos e relatórios
para escolas, professores e psicopedagogos.

- Site: https://sitejodospedagogicos.vercel.app/
- Jogos de exemplo (num carrossel): [Desafio das Peças com a Nágila](https://marcoaurello.github.io/jogoTabuleiro/),
  [My Day — English Academy](https://routinesgame.vercel.app/),
  [ABC da Tia ANA](https://abcdaana.vercel.app/) e
  [Jogo de Ortografia do Pleno](https://marcoaurello.github.io/jogoOrtografia/)
- Contato: WhatsApp (81) 98550-3305

## Na VPS (Dokploy)

O `Dockerfile` serve a página na raiz do domínio. Os jogos ficam no mesmo servidor, cada um como uma aplicação do Dokploy:
`/myday/` (DailyRoutinesGame), `/abc/` (jogoABC), `/ortografia/` (jogoOrtografia) e `/desafio/` (jogoTabuleiro).

## Arquivos
- `index.html`: a página (HTML e CSS num arquivo só).
- `assets/`: logo, imagem do relatório de exemplo, ícones e `og-image.jpg`
  (a imagem que aparece quando o link é compartilhado no WhatsApp).

© Marco Nunes — Todos os direitos reservados
