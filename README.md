# GYM MOCKUP

Template genérico de site para academia, de página única, com visual moderno (tema escuro com acento verde-limão). Auto-contido e pronto para personalizar: todas as imagens são locais e os contatos, redes sociais e localização usam placeholders.

## Screenshots

![Visão do topo da página](screenshots/screenshot001.png)

![Página completa](screenshots/screenshot002.png)

## Seções

- **Hero** — título, chamada e estatísticas com animação de contador
- **Sobre** — texto institucional com imagem e diferenciais
- **Serviços** — cards de serviços (aula experimental, planos, personal, nutrição, etc.)
- **Redes Sociais** — placeholders para redes da academia
- **Localização** — endereço placeholder e espaço para mapa
- **CTA** — chamada final com imagem de fundo
- **Footer** — marca e links de redes sociais

## Tecnologias

- HTML5, CSS3 e JavaScript puro (sem dependências de build)
- [Inter](https://fonts.google.com/specimen/Inter) (Google Fonts)
- [Font Awesome 6](https://fontawesome.com)
- Imagens de [Unsplash](https://unsplash.com) (licença gratuita), salvas localmente em `images/`

## Como usar

Abra o `index.html` diretamente no navegador.

## Personalização

Para usar em uma academia real, substitua os placeholders:

- `GYM MOCKUP` e frases do hero, sobre e CTA
- Cards de serviço e seus links (`href="#"`)
- Handles das redes sociais (`@sua_academia`) e links do footer
- `Endereço da sua academia` e o mapa em `#localizacao`
- Imagens em `images/` (`hero.jpg`, `about.jpg`, `cta.jpg`)

As cores da marca podem ser ajustadas nas variáveis do `:root` em `style.css` (por exemplo, `--green`).

## Estrutura

```
.
├── images/          # imagens do Unsplash (hero, sobre, cta)
├── screenshots/     # capturas de tela do template
├── index.html       # página única
├── style.css        # estilos
└── script.js        # menu mobile, reveal, contador e efeito do header
```
