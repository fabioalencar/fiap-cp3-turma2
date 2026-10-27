# Briefing 04 — Confeiteira

## Persona

**Marina Souza**, 34 anos, confeiteira. Faz bolos artísticos e doces finos para eventos. Atende sob encomenda em Curitiba, PR. Comunicação afetiva, delicada.

## Paleta

- Primária (fundo): `#FFF5F0` (rosé claro)
- Destaque: `#C58A6F` (terracota suave / nude)
- Acento: `#D4AF37` (dourado fosco)

## Tipografia

- **Playfair Display** (Google Fonts) para títulos — weight 700
- **Quicksand** (Google Fonts) para texto corrido — weight 400, 600

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Quicksand:wght@400;500;600&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Playfair Display", serif;
/* texto */
font-family: "Quicksand", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 130×130px
- Borda dourada 2px com pequeno espaçamento (4px de padding externo)

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/flor.svg` | Ornamento de flor (opcional) |

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

- Nome: **Marina Souza** (em Playfair, itálico)
- Profissão: `Confeitaria Artística`
- Slogan abaixo: *"Doces que contam histórias."*

## Botões de ação rápida (3)

- WhatsApp
- Instagram
- E-mail

Formato: ícone preenchido em terracota dentro de círculo dourado-claro, label embaixo em Quicksand.

## Links customizados (4) — seção "Encomendas"

- Bolos para aniversário
- Doces para casamento
- Cardápio completo (PDF)
- Depoimentos de clientes

Botões com fundo branco, borda dourada fina (1px), raio **20px** (bem arredondado), sombra suave.

## Detalhes visuais

- Raio: **20px** (visual macio)
- Modo: **claro fixo**
- Sombras suaves rosé (`0 4px 12px rgba(197,138,111,0.15)`)
- Pode incluir uma flor (`assets/icons/flor.svg`) no topo ou no rodapé

## Acabamento esperado

Sensação delicada, artesanal, premium-afetivo.
