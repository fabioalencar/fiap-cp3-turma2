# Briefing 01 — Personal Trainer

## Persona

**Beatriz Lima**, 28 anos, personal trainer especializada em hipertrofia feminina. Atende em academia parceira na Vila Madalena, SP. Energia alta, comunicação direta.

## Paleta

- Primária (fundo): `#0A0A0A` (preto absoluto)
- Destaque: `#C7FF3F` (verde-limão neon)
- Neutra (texto): `#FFFFFF`

## Tipografia

- **Inter** (Google Fonts) — pesos 400, 700, 900
- Título do nome em weight 900

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;900&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 120px de diâmetro
- Borda de 3px na cor de destaque

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |

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

- Nome: **Beatriz Lima**
- Profissão: `PERSONAL TRAINER` (uppercase, letter-spacing)
- Slogan abaixo: *"Treino que entrega resultado."*

## Botões de ação rápida (4)

- WhatsApp
- Ligar
- Instagram
- E-mail

Formato: ícone redondo verde-limão sobre fundo preto, label embaixo em branco.

## Links customizados (4) — seção "MEUS LINKS"

- Agendar avaliação física
- Programa "30 dias HIIT"
- Loja de suplementos parceira
- Canal no YouTube

Botões largura total, fundo branco com texto preto, cantos arredondados 12px.

## Detalhes visuais

- Raio dos cards/botões: **12px**
- Modo: **escuro fixo** (sem toggle)
- Sombras: nenhuma (estética flat dark)
- Footer com texto "© Beatriz Lima" centralizado

## Acabamento esperado

Sensação de academia moderna, alto contraste, energia.
