# Briefing 19 — Professora de Yoga

## Persona

**Júlia Andrade**, 34 anos, professora de yoga (Vinyasa e Yin). Estúdio próprio em Florianópolis, SC. Também atende online. Estética zen, natural, calma.

## Paleta

- Primária (fundo): `#EDE6D6` (areia clara)
- Destaque: `#6B7F5E` (verde-musgo)
- Acento: `#C39B7B` (terracota suave)

## Tipografia

- **Cormorant Garamond** (Google Fonts) para nome — weight 400, itálico
- **Karla** (Google Fonts) para texto — weight 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400&family=Karla:ital,wght@0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Cormorant Garamond", serif;
/* texto */
font-family: "Karla", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 130×130px
- Sem borda; deixar respirar com pelo menos 8px de padding ao redor

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/lotus.svg` | Ornamento de lótus (opcional) |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://wa.me/5511999999999">
  <img src="assets/icons/whatsapp.svg" alt="WhatsApp" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Júlia Andrade** (em Cormorant itálico, weight 400)
- Profissão: `Professora de Yoga · Vinyasa & Yin`
- Slogan abaixo: *"Respire. Permita-se chegar."*

## Botões de ação rápida (3)

- WhatsApp
- Instagram
- E-mail

Formato: ícone outline 1.5px verde-musgo, sem fundo, label embaixo em Karla 500 verde-musgo escuro.

## Links customizados (4) — seção "Práticas"

- Aulas presenciais (estúdio)
- Aulas online ao vivo
- Retiros & imersões
- Agendar aula experimental

Botões com fundo branco off-white (`#F7F2E7`), sem borda, raio **18px** (suave), texto verde-musgo escuro, ícone terracota à esquerda.

## Detalhes visuais

- Raio: **18px** (visual macio e orgânico)
- Modo: **claro fixo**
- Sem sombras (estética flat orgânica)
- MUITO espaçamento (padding 32-40px entre seções)
- Pode incluir uma flor de lótus (`assets/icons/lotus.svg`) como ornamento

## Acabamento esperado

Sensação zen, natural, retiro de yoga em montanha — sofisticação calma.
