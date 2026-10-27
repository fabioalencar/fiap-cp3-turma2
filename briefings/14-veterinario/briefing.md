# Briefing 14 — Veterinário

## Persona

**Dr. Pedro Yamada**, 35 anos, médico veterinário. Clínica própria especializada em cães e gatos. Atende em Londrina, PR. Comunicação amigável, dono de dois cachorros e três gatos.

## Paleta

- Primária (fundo): `#EAF6F1` (verde-água muito claro)
- Destaque: `#2D8A6B` (verde-pet)
- Acento: `#F2A742` (laranja-mostarda suave)

## Tipografia

- **Poppins** (Google Fonts) — pesos 400, 600, 700
- Nome em weight 700

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
- Borda 2px verde-pet

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
| `assets/icons/pata.svg` | Ornamento de patinha (opcional) |

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

- Nome: **Dr. Pedro Yamada**
- Profissão: `Médico Veterinário — CRMV-PR 12345`
- Slogan abaixo: *"Cuidado veterinário com carinho para sua família peluda."*

## Botões de ação rápida (4)

- WhatsApp
- Ligar
- E-mail
- Mapa

Formato: ícone preenchido verde-pet em fundo branco arredondado (círculo), label embaixo em Poppins 600.

## Links customizados (4) — seção "Serviços"

- Consulta de rotina
- Vacinação anual
- Emergência 24h
- Banho e tosa parceiro

Botões com fundo branco, sombra suave, ícone à esquerda em laranja-mostarda, texto em verde-pet, raio **14px**.

## Detalhes visuais

- Raio: **14px**
- Modo: **claro fixo**
- Sombras suaves verdes (`0 4px 14px rgba(45,138,107,0.12)`)
- Uma patinha (`assets/icons/pata.svg`) acima da foto; pode repetir como separador

## Acabamento esperado

Sensação amigável, profissional pet-friendly, organizado e acolhedor.
