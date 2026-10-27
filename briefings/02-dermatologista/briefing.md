# Briefing 02 — Dermatologista

## Persona

**Dr. Henrique Costa**, 42 anos, dermatologista. Consultório próprio em Pinheiros, SP. Especialista em dermatologia clínica e estética. Comunicação técnica e elegante.

## Paleta

- Primária (fundo): `#FAFAF7` (off-white)
- Destaque: `#1B2A3A` (azul-petróleo profundo)
- Neutra (texto secundário): `#6B7280`

## Tipografia

- **Lato** (Google Fonts) — pesos 400, 700
- Nome em weight 700

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Lato:ital,wght@0,400;0,700;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Lato", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato quadrado com cantos arredondados (raio 16px)
- 140×140px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://wa.me/5511999999999">
  <img src="assets/icons/whatsapp.svg" alt="WhatsApp" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Dr. Henrique Costa**
- Profissão: `Dermatologista — CRM 123456-SP`
- Slogan abaixo: *"Cuidado clínico e estético da sua pele."*

## Botões de ação rápida (3)

- WhatsApp
- Ligar
- E-mail

Formato: ícone outline azul-petróleo, label embaixo. Sem fundo, só ícone + texto.

## Links customizados (4) — seção "Atendimento"

- Agendar consulta
- Procedimentos estéticos
- Convênios aceitos
- Localização do consultório

Botões com fundo branco, borda 1px azul-petróleo, raio 8px.

## Detalhes visuais

- Raio dos botões: **8px**
- Modo: **claro fixo**
- Sombras: muito sutis (`0 1px 2px rgba(0,0,0,0.05)`) só nos cards principais
- Tipografia generosa, espaçamento confortável

## Acabamento esperado

Sensação de consultório premium, sóbrio, confiança médica.
