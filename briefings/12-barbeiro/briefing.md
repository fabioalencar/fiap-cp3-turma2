# Briefing 12 — Barbearia

## Persona

**Tito Barber** (Augusto "Tito" Ribeiro), 39 anos, dono da barbearia "Tito Barber Shop". Localizada em bairro de Salvador, BA. Estética vintage americana anos 1950, navalhada clássica.

## Paleta

- Primária (fundo): `#1F1611` (marrom-café escuro)
- Destaque: `#E8D5B0` (creme envelhecido / pergaminho)
- Acento: `#B8860B` (dourado-tabaco)

## Tipografia

- **Bebas Neue** (Google Fonts) para títulos — weight 400 (única disponível)
- **Lora** (Google Fonts) para texto — weight 400, 500 itálico

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue:wght@400&family=Lora:ital,wght@0,400;0,500;0,600;0,700;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Bebas Neue", sans-serif;
/* texto */
font-family: "Lora", serif;
```
<!-- /gerado:fontes -->

## Foto

- **Não usar foto pessoal** — usar o **logotipo**: as iniciais `T·B` com "BARBER · SHOP" dentro de um emblema circular cor pergaminho (pronto em `assets/logo.png`), 130×130px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/logo.png` | Logotipo pronto (512 × 512, fundo transparente). Não precisa desenhar: só ajuste o tamanho com CSS. |
| `assets/icons/calendar.svg` | Ícone do botão Agendar |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="#agendar">
  <img src="assets/icons/calendar.svg" alt="" width="22" height="22">
  <span>Agendar</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **TITO BARBER** (em Bebas Neue uppercase)
- Profissão: `Classic Barber Shop — Salvador / BA`
- Slogan abaixo: *"Cabelo, barba e tradição."*

## Botões de ação rápida (3)

- Agendar (link)
- WhatsApp
- Instagram

Formato: botão com fundo pergaminho, texto marrom-café em Bebas uppercase, borda dourada 1px, raio **2px**.

## Links customizados (4) — seção "SERVIÇOS"

- Cabelo + barba (combo)
- Barba navalhada quente
- Hidratação capilar
- Tabela de preços

Cards com fundo marrom mais claro (`#2A1D14`), borda dourada fina, raio **2px**, texto creme.

## Detalhes visuais

- Raio: **2px** (estética angular vintage)
- Modo: **escuro fixo**
- Pode incluir um padrão de listras finas (CSS gradient) no header — estilo poste de barbeiro
- Linhas decorativas douradas finas separando seções

## Acabamento esperado

Sensação de barbearia clássica americana, tradição masculina, atemporal.
