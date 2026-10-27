# Briefing 23 — Streamer / Criador de Conteúdo Gamer

## Persona

**Vinícius "Vinny" Gomes**, 24 anos, streamer e criador de conteúdo gamer. Foca em FPS competitivo e variety streams. Baseado em Belo Horizonte, MG. Estética ousada, jovem, energia digital.

## Paleta

- Primária (fundo): `#13001E` (roxo-quase-preto)
- Destaque 1: `#A855F7` (roxo neon)
- Destaque 2: `#84CC16` (lime neon)

## Tipografia

- **Press Start 2P** (Google Fonts) para nome — weight 400 (pixel-art style, usar com moderação)
- **Inter** (Google Fonts) para texto — weight 500, 700

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Press+Start+2P:wght@400&family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Press Start 2P", monospace;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato quadrado com cantos arredondados (raio 12px)
- 140×140px
- Aplicar `box-shadow` colorido tipo "glow" roxo + lime nas bordas

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/twitch.svg` | Ícone do botão Twitch |
| `assets/icons/youtube.svg` | Ícone do botão YouTube |
| `assets/icons/discord.svg` | Ícone do botão Discord |
| `assets/icons/twitter.svg` | Ícone do botão Twitter/X |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://twitch.tv/perfil">
  <img src="assets/icons/twitch.svg" alt="" width="22" height="22">
  <span>Twitch</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **VINNY GOMES** (em Press Start 2P, tamanho reduzido por causa da fonte)
- Profissão: `Streamer · FPS Competitivo · Variety`
- Slogan abaixo: *"Vê o tiro antes do tiro acontecer."*

## Botões de ação rápida (4)

- Twitch
- YouTube
- Discord
- Twitter/X

Formato: ícone preenchido lime dentro de quadrado roxo (raio 8px), label embaixo em Inter 700 lime.

## Links customizados (3) — seção ">> LATEST"

- Próximo torneio
- Loja oficial (camisas)
- Apoie no Picpay

Cards com fundo `#1F0033` (roxo um pouco mais claro), borda 2px lime, raio 8px, label em Inter 700 branco com `>` antes.

## Detalhes visuais

- Raio: **8px**
- Modo: **escuro fixo**
- Glow neon: `box-shadow: 0 0 16px rgba(168,85,247,0.4)` em hover dos botões
- Pode incluir uma faixa diagonal lime no header como detalhe esports
- Padrão de "scan lines" CSS sutil opcional no background

## Acabamento esperado

Sensação esports/twitch, energia jovem, agressividade visual, cyber-juvenil.
