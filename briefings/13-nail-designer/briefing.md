# Briefing 13 — Nail Designer

## Persona

**Bia Nails** (Beatriz Camargo), 26 anos, nail designer e podóloga. Estúdio próprio em Campinas, SP. Especialidade em nail art autoral. Estética glam, feminina, brilhante.

## Paleta

- Primária (fundo): `#FFF0F5` (rosa-bebê)
- Destaque: `#C71585` (magenta vibrante)
- Acento: `#F8D7DA` (rosa-perolado)

## Tipografia

- **Poppins** (Google Fonts) para tudo — pesos 300, 600, 800
- Nome em weight 800, com pequenos brilhos (emoji ou `assets/icons/brilho.svg`) opcionais

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Poppins", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 130×130px
- Borda gradiente magenta→rosa-perolado de 3px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/tiktok.svg` | Ícone do botão TikTok |
| `assets/icons/map.svg` | Ícone do botão Mapa |
| `assets/icons/brilho.svg` | Ornamento de brilho/estrela (opcional) |

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

- Nome: **Bia Nails**
- Profissão: `Nail Designer · Especialista em Russian Manicure`
- Slogan abaixo: *"Unhas dos sonhos, do design ao detalhe."*

## Botões de ação rápida (4)

- WhatsApp
- Instagram
- TikTok
- Mapa

Formato: ícone preenchido magenta dentro de círculo branco com sombra rosa, label embaixo em Poppins 600 magenta.

## Links customizados (3) — seção "Serviços"

- Agendar horário (Booksy)
- Cardápio de nail art
- Pacote noiva (mãos + pés)

Botões com fundo branco, borda magenta 1.5px, raio **16px**, texto magenta semibold.

## Detalhes visuais

- Raio: **16px**
- Modo: **claro fixo**
- Sombras rosadas (`0 6px 20px rgba(199,21,133,0.15)`)
- Pode incluir glitter/brilho via `background-image` gradiente sutil no header

## Acabamento esperado

Sensação glam, feminina, vibrante, "instagramável".
