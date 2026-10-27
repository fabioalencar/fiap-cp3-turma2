# Briefing 11 — Fotógrafo de Casamento

## Persona

**Rafael Monteiro**, 33 anos, fotógrafo de casamento. Estúdio em Porto Alegre, RS, atende em todo o Sul. Estilo documental/fine art. Visual editorial.

## Paleta

- Primária (fundo): `#FFFFFF` (branco puro)
- Destaque: `#0A0A0A` (preto)
- Acento: `#B8A88A` (champagne fosco)

## Tipografia

- **Cormorant Garamond** (Google Fonts) para nome — weight 400, light + itálico
- **Inter** (Google Fonts) para texto — weight 400

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400&family=Inter:ital,wght@0,300;0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Cormorant Garamond", serif;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato quadrado com cantos retos (0px)
- 150×150px
- Foto em preto e branco (a `assets/foto.png` já vem P&B)

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). Já vem em preto e branco. O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="mailto:contato@exemplo.com">
  <img src="assets/icons/email.svg" alt="E-mail" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Rafael Monteiro** (em Cormorant itálico, weight 400)
- Profissão: `Wedding Photographer · Fine Art`
- Slogan abaixo: *"Documentando o que não se repete."*

## Botões de ação rápida (3)

- E-mail
- Instagram
- WhatsApp

Formato: apenas ícone outline preto, 1.5px stroke, sem fundo. Label embaixo em Inter 400 lowercase.

## Links customizados (3) — seção "PORTFOLIO"

- Ensaios pré-wedding
- Casamentos 2025
- Investimento (PDF)

Botões com apenas linha superior 1px champagne, sem fundo, sem borda lateral — visual editorial / minimalismo de revista.

## Detalhes visuais

- Raio: **0px**
- Modo: **claro fixo**
- Sem sombras
- Espaçamento muito generoso (padding 32-48px)
- Pode incluir uma linha fina champagne separando seções

## Acabamento esperado

Sensação editorial, fine art, atemporal — visual de portfólio de fotógrafo premium.
