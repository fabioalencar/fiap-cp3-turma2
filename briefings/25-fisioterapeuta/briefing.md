# Briefing 25 — Fisioterapeuta esportivo

## Persona

**Lucas Ferraz**, 31 anos, fisioterapeuta esportivo. Atende corredores e atletas de fim de semana numa clínica na Mooca, SP. Explica o tratamento passo a passo, sem jargão.

## Paleta

- Primária (fundo): `#F3F6FB` (cinza-azulado bem claro)
- Destaque: `#1E4FD8` (azul-cobalto)
- Acento: `#FF7A1A` (laranja)

## Tipografia

- **DM Sans** (Google Fonts) — pesos 400, 500, 700
- Nome em weight 700

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "DM Sans", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 124px de diâmetro
- Borda de 3px azul-cobalto

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/calendar.svg` | Ícone do botão Agendar |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |

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

- Nome: **Lucas Ferraz**
- Profissão: `FISIOTERAPEUTA ESPORTIVO` (uppercase, letter-spacing, azul-cobalto)
- Registro abaixo: `CREFITO-3 123456-F` (pequeno, uppercase, cinza)
- Slogan: *"De volta ao jogo, sem pular etapas."*

## Botões de ação rápida (4)

- WhatsApp
- Ligar
- Agendar
- Instagram

Formato: ícone dentro de círculo azul-cobalto preenchido, ícone na cor do fundo, label embaixo em azul-escuro.

## Links customizados (4) — seção "TRATAMENTOS"

- Avaliação de lesão esportiva
- Reabilitação de joelho e tornozelo
- Liberação miofascial
- Planos para corredores

Botões largura total, fundo branco, borda 1px azul-cobalto, raio **14px**, texto em weight 600 e seta `→` à direita.

## Detalhes visuais

- Raio dos botões: **14px**; o cartão tem raio maior (21px)
- Modo: **claro fixo**
- Sombra suave no cartão (`0 4px 24px rgba(0,0,0,0.06)`)
- Faixa fina no topo do cartão com degradê azul-cobalto → laranja (4px de altura)
- Footer com `© 2026 Lucas Ferraz` centralizado

## Acabamento esperado

Clínica esportiva moderna: limpa, confiante, com energia no laranja sem perder a seriedade da saúde.
