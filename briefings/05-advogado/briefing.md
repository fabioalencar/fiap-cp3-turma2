# Briefing 05 — Advogado Tributarista

## Persona

**Dr. Felipe Tavares**, 51 anos, advogado tributarista. Sócio de banca em Brasília, DF. Atende grandes empresas. Comunicação formal, conservadora.

## Paleta

- Primária (fundo): `#0E1B2C` (navy profundo)
- Destaque: `#C9A24E` (dourado fosco)
- Neutra (texto): `#E8E6E1` (off-white)

## Tipografia

- **Cormorant Garamond** (Google Fonts) para títulos — weight 600
- **Inter** (Google Fonts) para texto — weight 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Inter:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
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

- **Visível**, formato quadrado com cantos arredondados sutis (raio 6px)
- 130×130px
- Sem borda decorativa

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/linkedin.svg` | Ícone do botão LinkedIn |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="tel:+5511999999999">
  <img src="assets/icons/phone.svg" alt="Ligar" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Dr. Felipe Tavares**
- Profissão: `Advogado Tributarista — OAB/DF 12.345`
- Slogan abaixo: *"Excelência em direito tributário corporativo."*

## Botões de ação rápida (3)

- Ligar
- E-mail
- LinkedIn

Formato: ícone outline dourado, label embaixo em off-white. Sem fundo.

## Links customizados (4) — seção "Áreas de atuação"

- Planejamento tributário
- Contencioso fiscal
- Recuperação de créditos
- Agendar reunião

Botões com fundo navy escuro (mais claro que o background), borda dourada 1px, raio **2px** (quase reto).

## Detalhes visuais

- Raio: **2px** (cantos formais)
- Modo: **escuro fixo**
- Sem sombras (estética flat sóbria)
- Linhas divisórias finas douradas entre seções

## Acabamento esperado

Sensação institucional, peso, autoridade jurídica.
