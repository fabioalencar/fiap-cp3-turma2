# Briefing 27 — Sommelier

## Persona

**Theo Ramos**, 41 anos, sommelier. Faz degustações em casa, harmonização para jantares e monta cartas de vinho para restaurantes em Porto Alegre, RS. Fala de vinho sem pose.

## Paleta

- Primária (fundo): `#2B0F17` (bordô bem escuro)
- Destaque: `#E8C07A` (dourado-mel)
- Acento: `#B84A5E` (vinho-rosé)

## Tipografia

- **Bodoni Moda** (Google Fonts) para o nome — weight 500
- **Jost** (Google Fonts) para texto — weight 300, 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bodoni+Moda:wght@500;700&family=Jost:ital,wght@0,300;0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Bodoni Moda", serif;
/* texto */
font-family: "Jost", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, quadrada com cantos arredondados (10px), 124 × 124px
- Borda 1px dourado-mel com 6px de espaço entre a borda e a foto

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/map.svg` | Ícone do botão Mapa |

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

- Nome: **Theo Ramos** (Bodoni Moda)
- Profissão: `SOMMELIER · CURADORIA DE VINHOS` (uppercase, letter-spacing, dourado-mel)
- Slogan: *"Cada garrafa tem uma história para contar."* (itálico)

## Botões de ação rápida (4)

- WhatsApp
- Instagram
- E-mail
- Mapa

Formato: ícone dourado dentro de círculo só com contorno (1px dourado, sem fundo), label embaixo em off-white.

## Links customizados (4) — seção "EXPERIÊNCIAS"

- Degustação guiada em casa
- Harmonização para jantares
- Clube do vinho (assinatura)
- Carta para restaurantes

Cards com fundo bordô um pouco mais claro (`#3A1520`), borda 1px dourado-mel, raio **4px**, texto off-white, seta `→` dourada à direita.

## Detalhes visuais

- Raio: **4px**
- Modo: **escuro fixo**
- Sem sombras
- Linha fina vinho-rosé no topo do cartão
- Footer com `© 2026 Theo Ramos`

## Acabamento esperado

Adega elegante à meia-luz: escuro, quente, dourado na medida certa, sem ostentação.
