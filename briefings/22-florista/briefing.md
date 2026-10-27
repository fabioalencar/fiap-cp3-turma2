# Briefing 22 — Florista

## Persona

**Helena Prado**, 39 anos, florista. Ateliê próprio especializado em arranjos para casamentos e eventos. Atende em São Paulo, SP. Estética botânica, orgânica, artesanal.

## Paleta

- Primária (fundo): `#F0EDE2` (creme natural)
- Destaque: `#557653` (verde-folhagem)
- Acento: `#E89B8B` (pêssego suave)

## Tipografia

- **Fraunces** (Google Fonts) para nome — weight 500 itálico (estética botânica vintage)
- **Inter** (Google Fonts) para texto — weight 400

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fraunces:ital,wght@0,400;0,500;1,500&family=Inter:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Fraunces", serif;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Não usar foto pessoal** — usar o **logotipo**: monograma `HP` em Fraunces dentro de um círculo verde-folhagem (pronto em `assets/logo.png`), 130×130px
- Um pequeno ramo (`assets/icons/ramo.svg`) acima do logotipo

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/logo.png` | Logotipo pronto (512 × 512, fundo transparente). Não precisa desenhar: só ajuste o tamanho com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/ramo.svg` | Ornamento de ramo (opcional) |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://wa.me/5511999999999">
  <img src="assets/icons/whatsapp.svg" alt="" width="22" height="22">
  <span>WhatsApp</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Helena Prado** (em Fraunces 500 itálico)
- Profissão: `Ateliê Floral · Casamentos & Eventos`
- Slogan abaixo: *"Flores que contam histórias."*

## Botões de ação rápida (3)

- WhatsApp
- Instagram
- E-mail

Formato: ícone preenchido verde-folhagem dentro de círculo creme com borda fina, label embaixo em Inter 400 pêssego escuro.

## Links customizados (4) — seção "Trabalhos"

- Arranjos para casamento
- Buquês & ramos de noiva
- Eventos corporativos
- Encomende um arranjo

Botões com fundo branco, borda 1px verde-folhagem, raio **20px** (orgânico), texto verde-folhagem escuro, ícone pêssego à esquerda.

## Detalhes visuais

- Raio: **20px** (estética orgânica)
- Modo: **claro fixo**
- Sombras suaves verdes (`0 4px 14px rgba(85,118,83,0.10)`)
- Pode repetir o ramo (`assets/icons/ramo.svg`) como ornamento entre seções
- Tipografia generosa, espaçamento confortável

## Acabamento esperado

Sensação de ateliê floral artesanal, botânico, romântico-natural.
