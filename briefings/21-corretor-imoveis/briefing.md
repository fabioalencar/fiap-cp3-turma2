# Briefing 21 — Corretor de Imóveis

## Persona

**Cláudio Bittencourt**, 52 anos, corretor de imóveis. Especialista em imóveis de alto padrão em Balneário Camboriú, SC. CRECI ativo. Comunicação confiável, formal-acessível.

## Paleta

- Primária (fundo): `#F2EEE7` (bege-pedra)
- Destaque: `#1F3A5F` (azul-petróleo)
- Acento: `#A68A5C` (mostarda fosco)

## Tipografia

- **Libre Baskerville** (Google Fonts) para nome — weight 700
- **Inter** (Google Fonts) para texto — weight 400, 600

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Libre+Baskerville:wght@400;700&family=Inter:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Libre Baskerville", serif;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato quadrado com cantos arredondados (raio 4px)
- 130×130px
- Sem borda decorativa

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
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

- Nome: **Cláudio Bittencourt**
- Profissão: `Corretor de Imóveis — CRECI/SC 12345-F`
- Slogan abaixo: *"Imóveis de alto padrão · Balneário Camboriú."*

## Botões de ação rápida (4)

- WhatsApp
- Ligar
- E-mail
- Mapa (escritório)

Formato: botão retangular com fundo azul-petróleo, ícone à esquerda + label à direita em Inter 600 branco, raio 4px.

## Links customizados (4) — seção "Portfólio"

- Apartamentos frente-mar
- Coberturas exclusivas
- Pré-lançamentos
- Agende uma visita

Cards com fundo branco, borda 1px mostarda fina, raio 4px, label em Libre Baskerville 700 azul-petróleo + sublabel em Inter cinza.

## Detalhes visuais

- Raio: **4px** (cantos formais)
- Modo: **claro fixo**
- Sombras muito sutis (`0 1px 2px rgba(0,0,0,0.05)`)
- Linha mostarda 1px separando header do conteúdo
- Pode incluir o selo CRECI como badge no header

## Acabamento esperado

Sensação de mercado de alto padrão, confiança institucional, imobiliária premium tradicional.
