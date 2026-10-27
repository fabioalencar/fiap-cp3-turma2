# Briefing 26 — Professora de inglês

## Persona

**Nina Okada**, 34 anos, professora de inglês e tradutora. Dá aulas particulares online e em grupos pequenos, de Curitiba, PR. Morou cinco anos em Londres. Gosta de livros, de revista impressa e de aula sem apostila.

## Paleta

- Primária (fundo): `#FBF6EE` (creme de papel)
- Destaque: `#C8402B` (vermelho-tomate)
- Acento: `#1D3557` (azul-tinta)

## Tipografia

- **Instrument Serif** (Google Fonts) para o nome — weight 400 itálico
- **Instrument Sans** (Google Fonts) para texto — weight 400, 500, 600

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Instrument+Serif:ital,wght@0,400;1,400&family=Instrument+Sans:ital,wght@0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Instrument Serif", serif;
/* texto */
font-family: "Instrument Sans", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, retangular vertical (retrato), 120 × 150px
- Cantos quase retos (2px), sem borda

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 640, retrato). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://wa.me/5511999999999">
  <img src="assets/icons/whatsapp.svg" alt="WhatsApp" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Nina Okada** (Instrument Serif itálico, grande)
- Profissão: `ENGLISH TEACHER · TRADUTORA` (uppercase, letter-spacing, vermelho-tomate)
- Slogan: *"Inglês para a vida real, não para a prova."* (itálico, cinza)

## Botões de ação rápida (3)

- WhatsApp
- E-mail
- Instagram

Formato: só o ícone em contorno fino (1.5px), vermelho-tomate, sem fundo e sem texto embaixo. O nome do botão vai no `alt`.

## Links customizados (4) — seção "AULAS"

- Conversação para adultos
- Inglês para entrevistas de emprego
- Aulas em grupo (até 4 alunos)
- Tradução de documentos

Sem caixa: cada link é uma linha com borda inferior fina, texto à esquerda e seta `→` azul-tinta à direita.

## Detalhes visuais

- Raio: **0** (estética editorial, de revista)
- Modo: **claro fixo**
- Sem sombras
- Linha fina azul-tinta separando o cabeçalho dos botões
- Espaçamento generoso (respiro de página impressa)
- Footer com `© 2026 Nina Okada`

## Acabamento esperado

Editorial, calmo e culto, como a página de uma revista literária, com o vermelho dando personalidade.
