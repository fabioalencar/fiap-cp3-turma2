# Briefing 15 — Tatuador

## Persona

**Lobo Ink** (Bruno "Lobo" Camargo), 31 anos, tatuador. Estúdio próprio especializado em blackwork e fineline. Atende em Curitiba, PR. Estética dark/alternative.

## Paleta

- Primária (fundo): `#0F0F0F` (preto-fumaça)
- Destaque: `#E5E5E5` (cinza-claro)
- Acento: `#7A0E0E` (vinho escuro)

## Tipografia

- **Cinzel** (Google Fonts) para nome — weight 600 (tipo gótico/lapidar)
- **JetBrains Mono** (Google Fonts) para texto/labels — weight 400 (mono, estética técnica)

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cinzel:wght@600&family=JetBrains+Mono:wght@400;500;600;700&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Cinzel", serif;
/* texto */
font-family: "JetBrains Mono", monospace;
```
<!-- /gerado:fontes -->

## Foto

- **Não usar foto pessoal** — usar o **logotipo**: a palavra `LOBO` com um triângulo acima, dentro de um círculo com borda dupla (pronto em `assets/logo.png`), 130×130px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/logo.png` | Logotipo pronto (512 × 512, fundo transparente). Não precisa desenhar: só ajuste o tamanho com CSS. |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://instagram.com/perfil">
  <img src="assets/icons/instagram.svg" alt="Instagram" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **LOBO INK** (em Cinzel uppercase)
- Profissão: `Blackwork · Fineline · Botanical`
- Slogan abaixo: *"Tatuagem como ritual. Curitiba — PR."*

## Botões de ação rápida (3)

- Instagram
- WhatsApp
- E-mail

Formato: ícone outline 1.5px cinza-claro, sem fundo, label embaixo em JetBrains Mono lowercase.

## Links customizados (4) — seção "STUDIO"

- Agendar consulta
- Catálogo blackwork
- Cuidados pós-tatuagem
- Localização

Cards com fundo preto, borda 1px cinza-claro, raio **0px**. Label à esquerda em mono, seta `→` à direita.

## Detalhes visuais

- Raio: **0px** (estética angular dark)
- Modo: **escuro fixo**
- Sem sombras
- Detalhe vinho escuro em separadores ou foco de botão
- Pode incluir uma linha vermelho-vinho fina no topo do header como detalhe

## Acabamento esperado

Sensação ritual, dark, ocultismo contemporâneo, estúdio sério de tattoo art.
