# Briefing 18 — Coach Financeiro

## Persona

**Marcos Andrade**, 45 anos, coach financeiro e planejador pessoal. CFP® certificado. Atende online em todo Brasil. Comunicação confiável, didática, conservadora-acessível.

## Paleta

- Primária (fundo): `#F5F4F0` (off-white quente)
- Destaque: `#1B4332` (verde-floresta escuro)
- Acento: `#7C7C7C` (cinza-grafite)

## Tipografia

- **Source Serif 4** (Google Fonts) para nome — weight 600
- **Source Sans 3** (Google Fonts) para texto — weight 400, 600

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Source+Serif+4:wght@600&family=Source+Sans+3:ital,wght@0,400;0,500;0,600;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Source Serif 4", serif;
/* texto */
font-family: "Source Sans 3", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 125×125px
- Borda 2px verde-floresta com 3px de padding interno

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/linkedin.svg` | Ícone do botão LinkedIn |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="mailto:contato@exemplo.com">
  <img src="assets/icons/email.svg" alt="" width="22" height="22">
  <span>E-mail</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Marcos Andrade, CFP®**
- Profissão: `Planejador Financeiro Pessoal · CFP® 12345`
- Slogan abaixo: *"Disciplina, dados e tempo. Seu futuro construído."*

## Botões de ação rápida (3)

- E-mail
- LinkedIn
- WhatsApp

Formato: botão retangular largura intermediária, fundo verde-floresta, ícone à esquerda + label à direita em Sans 600 branco, raio 6px.

## Links customizados (4) — seção "Como posso ajudar"

- Diagnóstico financeiro gratuito
- Planejamento de aposentadoria
- Investimentos para iniciantes (curso)
- Agendar uma conversa

Cards com fundo branco, borda 1px cinza-grafite suave, raio 6px, label em Serif 600 verde-floresta + sublabel pequena em cinza.

## Detalhes visuais

- Raio: **6px**
- Modo: **claro fixo**
- Sombras sutis (`0 1px 3px rgba(0,0,0,0.06)`)
- Linha fina verde-floresta separando o header da seção de ações
- Pode incluir um pequeno selo "CFP®" como badge

## Acabamento esperado

Sensação de profissional sério, banco premium, planejamento financeiro tradicional moderno.
