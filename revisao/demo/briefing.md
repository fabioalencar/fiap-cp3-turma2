# Briefing DEMO — Ceramista (aula de revisão)

> Este briefing não é de nenhum aluno. Serve para a aula de revisão: lemos juntos e montamos o cartão ao vivo.

## Persona

**Rita Moura**, 38 anos, ceramista. Tem um ateliê pequeno em Embu das Artes, SP, onde dá oficinas de torno e faz louça para restaurantes.

## Paleta

- Fundo da página: `#F4EDE4` (argila clara)
- Cartão: `#FFFFFF`
- Destaque: `#B5532F` (terracota)
- Texto: `#2B211C` · texto secundário: `#7A6A60` · bordas: `#E5D6C8`

## Tipografia

- **Young Serif** (Google Fonts) para o nome — weight 400
- **Work Sans** (Google Fonts) para texto — weight 400, 500, 600 e 400 itálico

### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Young+Serif&family=Work+Sans:ital,wght@0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Young Serif", serif;
/* texto */
font-family: "Work Sans", sans-serif;
```

## Foto

- **Visível**, circular, 120px de diâmetro
- Borda de 3px terracota

## Arquivos que você recebe

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm brancos: use com `<img>`, dentro do círculo terracota.

## Cabeçalho

- Nome: **Rita Moura** (Young Serif, 30px)
- Profissão: `CERAMISTA` (uppercase, letter-spacing, terracota)
- Slogan: *"Peças feitas à mão, uma de cada vez."* (itálico, cinza)

## Botões de ação rápida (4)

- WhatsApp
- Ligar
- Instagram
- E-mail

Formato: ícone branco dentro de círculo terracota de 52px, label embaixo. No hover, o círculo escurece (`#8E3F22`).

## Links customizados (3) — seção "ATELIÊ"

- Loja online
- Oficinas de torno
- Encomendas para restaurantes

Botões largura total, fundo branco, borda 1px `#E5D6C8`, raio **12px**, seta `→` à direita. No hover, a borda fica terracota.

## Detalhes visuais

- Cartão com largura máxima de 380px, centralizado, raio 24px
- Sombra suave no cartão (`0 4px 24px rgba(0, 0, 0, 0.06)`)
- Modo: **claro fixo**
- Footer com `© 2026 Rita Moura`, separado por uma linha fina

## Acabamento esperado

Ateliê de cerâmica: quente, calmo, artesanal, sem enfeite sobrando.
