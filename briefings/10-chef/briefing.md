# Briefing 10 — Chef de Cozinha Italiana

## Persona

**Chef Lorenzo Bianchi**, 44 anos, chef de cozinha italiana. Atende eventos privados e jantares fechados em São Paulo. Filho de italianos, fala da cozinha como história de família.

## Paleta

- Primária (fundo): `#FBF7F2` (creme pergaminho)
- Destaque: `#8C3A2A` (terracota escuro / vinho-tijolo)
- Acento: `#2F4F2F` (verde-oliva escuro)

## Tipografia

- **Cormorant Garamond** (Google Fonts) para nome e títulos — weight 500, 700
- **Lora** (Google Fonts) para corpo — weight 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,500&family=Lora:ital,wght@0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Cormorant Garamond", serif;
/* texto */
font-family: "Lora", serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato retangular vertical (proporção 4:5), 120×150px
- Cantos retos (0px) — aparência editorial / livro de receitas

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 640, retrato). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/brilho.svg` | Ornamento de brilho/estrela (opcional) |
| `assets/icons/ramo.svg` | Ornamento de ramo (opcional) |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://wa.me/5511999999999">
  <img src="assets/icons/whatsapp.svg" alt="WhatsApp" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Chef Lorenzo Bianchi** (em Cormorant 500, itálico)
- Profissão: `Cucina italiana di famiglia`
- Slogan abaixo: *"Da nonna alla tavola. Eventi privati em SP."*

## Botões de ação rápida (3)

- WhatsApp
- E-mail
- Instagram

Formato: ícone outline terracota, label embaixo em Lora itálico.

## Links customizados (4) — seção "Esperienze"

- Jantar romântico para 2
- Evento privado (até 20 pessoas)
- Aulas de pasta artesanal
- Cardápios e degustação

Cards com fundo branco, borda fina terracota 1px, raio **2px**, sombra muito sutil.

## Detalhes visuais

- Raio: **2px** (cantos quase retos, livro de receitas)
- Modo: **claro fixo**
- Três estrelinhas (`assets/icons/brilho.svg`) no topo do cartão; pode usar o ramo (`assets/icons/ramo.svg`) entre seções
- Sombras muito discretas

## Acabamento esperado

Sensação de menu de restaurante italiano artesanal, tradição, cuidado.
