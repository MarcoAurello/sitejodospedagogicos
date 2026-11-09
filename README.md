# Games Pedagógicos · site

Landing page da plataforma de jogos psicopedagógicos para crianças de 4 a 14 anos:
jogos, habilidades, identificação precoce das dificuldades, prints da plataforma,
identidade visual da escola, vídeos e competições criadas a partir de uma foto ou PDF.

- App dos jogos: https://gamespedagogicos.store/
- Vídeos: [apresentação](https://youtu.be/Ch8QlP4UpyI) e [área de gestão](https://youtu.be/Po1L_m7XyQw)
- Contato: WhatsApp (81) 98550-3305 (botões "Clique para testar grátis")

## Arquivos
- `index.html`: a página (HTML, CSS e JS num arquivo só).
- `assets/jogos/`: capas dos jogos do carrossel.
- `assets/prints/`: prints da plataforma (do manual do app).
- `assets/fotos/`: fotos dos alunos usando o app.
- `assets/icones/`: ícones Phosphor (fill), servidos localmente.
- `assets/`: logo, favicon e `og-image.jpg` (imagem do link compartilhado).

## Ver no computador
```
python -m http.server 5510
```
e abra http://127.0.0.1:5510/

## Na VPS (Dokploy)
O `Dockerfile` serve a página com nginx na raiz do domínio (Build Type = Dockerfile, porta 80).

© Marco Nunes. Todos os direitos reservados.
