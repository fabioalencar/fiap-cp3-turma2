# Briefing 06 — DJ / Produtor Musical

## Persona

**DJ Kael** (Caio Mendes), 26 anos, DJ e produtor de house/techno. Toca em festivais e clubs em São Paulo e circuito sul. Estética visual ousada.

## Paleta

- Primária (fundo): `#0B0014` (roxo-preto)
- Destaque 1: `#FF2E93` (rosa neon)
- Destaque 2: `#00E5FF` (ciano neon)

## Tipografia

- **Space Grotesk** (Google Fonts) — pesos 500, 700
- Nome em weight 700, tracking aberto

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Space Grotesk", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato quadrado sem cantos arredondados (0px)
- 140×140px
- Borda em gradiente rosa→ciano: a foto fica dentro de um elemento com `padding: 3px` e `background: linear-gradient(135deg, #FF2E93, #00E5FF)`

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/spotify.svg` | Ícone do botão Spotify |
| `assets/icons/soundcloud.svg` | Ícone do botão SoundCloud |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://open.spotify.com/">
  <img src="assets/icons/spotify.svg" alt="" width="22" height="22">
  <span>Spotify</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **DJ KAEL** (uppercase, letter-spacing 4px)
- Profissão: `Producer · DJ · Live Performer`
- Slogan abaixo: *"Underground house from São Paulo."*

## Botões de ação rápida (4)

- Spotify
- SoundCloud
- Instagram
- E-mail (para booking)

Formato: ícone branco dentro de quadrado com fundo em gradiente rosa→ciano, label embaixo em branco, uppercase.

## Links customizados (3) — seção "LATEST"

- Próximos shows
- Último EP — "NEON DRIFT"
- Press kit (PDF)

Botões com fundo `#1A0428` (roxo um pouco mais claro), borda 1px em rosa neon, raio **0px**.

## Detalhes visuais

- Raio: **0px** (estética angular)
- Modo: **escuro fixo**
- Glow neon nos botões em hover (`box-shadow: 0 0 20px rgba(255,46,147,0.6)`)
- Pode usar uma faixa gradiente rosa→ciano no topo ou separadores

## Acabamento esperado

Sensação cyberpunk/vaporwave, energia noturna, contemporâneo.
