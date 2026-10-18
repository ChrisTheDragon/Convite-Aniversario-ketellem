# Convite de Aniversário — Ketellem Castro

Convite interativo para os 18 anos de Ketellem Castro, responsivo e otimizado para dispositivos móveis. O projeto utiliza HTML, CSS e JavaScript puros, com animação de virar páginas através do Swiper.js.

## Link do convite

> Substitua o endereço abaixo pelo link publicado no GitHub Pages.

**Acessar convite:** [CONVITE](https://christhedragon.github.io/Convite_casamento_irnand/)

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript puro
- [Swiper.js](https://swiperjs.com/) via CDN
- Google Fonts:
  - Cormorant Garamond
  - Great Vibes
  - Montserrat

## Estrutura do convite

```text
.
├── Capa de abertura: assets/images/Capa_convite.jpeg
├── Página 1 — festa: assets/images/img_1.webp
├── Página 2 — dress code e botões: assets/images/img_2.webp
├── Página 3 — agradecimento: assets/images/img_3.webp
├── Imagem de compartilhamento: assets/images/Cover_convite.png
└── Música: assets/audio/audio.mp3
```

## Páginas

- **Capa:** abre o convite e inicia a música ao tocar no selo.
- **Festa:** apresenta o nome, a idade, a data, o horário e o local.
- **Dress code:** descreve o traje social e oferece os botões de localização e confirmação de presença.
- **Agradecimento:** encerra o convite com uma mensagem para os convidados.

## Personalização

No `index.html`, substitua os links temporários `href="#"` dos botões **Como chegar** e **Confirmar presença** pelos links do Google Maps e WhatsApp quando estiverem disponíveis. Os estilos e a configuração das imagens ficam em `css/styles.css`.

- O projeto não requer Node.js, compilação ou dependências locais.
- O layout foi desenvolvido com foco em dispositivos móveis.
- O `overflow` vertical é bloqueado para evitar rolagem indesejada no livro de páginas.
- O Swiper.js é carregado por CDN; para funcionar offline, será necessário baixar e hospedar a biblioteca localmente.
