# Briefing 20 — Maquiadora Profissional

## Persona

**Suelen Reis**, 31 anos, maquiadora profissional especializada em noivas e produções editoriais. Atende em Rio de Janeiro, RJ. Estética sofisticada, glam-elegante.

## Paleta

- Primária (fundo): `#0F0A08` (preto-café)
- Destaque: `#D4B896` (champagne fosco)
- Acento: `#B07158` (rosé-bronze)

## Tipografia

- **Italiana** (Google Fonts) para nome — weight 400 (estética alta-costura)
- **Montserrat** (Google Fonts) para texto — weight 300, 500 (letras finas e elegantes)

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Italiana:wght@400&family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Italiana", serif;
/* texto */
font-family: "Montserrat", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 140×140px
- Borda 1px champagne com 6px de padding externo
- A foto já vem tratada para o look editorial (não precisa de `filter`)

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://wa.me/5511999999999">
  <img src="assets/icons/whatsapp.svg" alt="WhatsApp" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Suelen Reis** (em Italiana, alta serifa)
- Profissão: `Maquiagem Profissional · Noivas & Editorial`
- Slogan abaixo: *"A beleza com sua assinatura."*

## Botões de ação rápida (3)

- WhatsApp
- Instagram
- E-mail

Formato: ícone outline 1px champagne, sem fundo, label embaixo em Montserrat 300 uppercase com letter-spacing.

## Links customizados (4) — seção "Serviços"

- Make noiva (com prova)
- Pacote madrinhas
- Editorial / produção
- Curso de automaquiagem

Botões transparentes com apenas linha inferior 1px champagne entre eles. Sem fundo, sem cards — visual de menu editorial. Label em Montserrat 300 com tracking aberto.

## Detalhes visuais

- Raio: **0px** (estética editorial / alta-costura)
- Modo: **escuro fixo**
- Sem sombras
- Linhas champagne muito finas (1px) como divisores
- Espaçamento generoso

## Acabamento esperado

Sensação de revista Vogue, salon premium do Rio, sofisticação noturna.
