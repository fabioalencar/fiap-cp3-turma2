# Briefing 17 — UX/UI Designer

## Persona

**Pedro Tanaka**, 29 anos, UX/UI designer freelancer. Trabalha remoto de São Paulo para clientes em fintech e SaaS. Estética tech minimalista, comunicação direta e visual.

## Paleta

- Primária (fundo): `#0E0E12` (quase-preto azulado)
- Destaque: `#5B8DEF` (azul-elétrico)
- Neutra (texto): `#E5E7EB`

## Tipografia

- **JetBrains Mono** (Google Fonts) — pesos 400, 700 — para títulos e labels (estética técnica)
- **Inter** (Google Fonts) para corpo — weight 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;700&family=Inter:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "JetBrains Mono", monospace;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, formato quadrado com cantos arredondados (raio 8px)
- 130×130px
- Foto levemente dessaturada (a `assets/foto.png` já vem assim; não precisa de `filter`)

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). Já vem com o filtro do briefing aplicado. O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/linkedin.svg` | Ícone do botão LinkedIn |
| `assets/icons/github.svg` | Ícone do botão GitHub |
| `assets/icons/calendar.svg` | Ícone do botão Agendar |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="mailto:contato@exemplo.com">
  <img src="assets/icons/email.svg" alt="E-mail" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Pedro Tanaka** (em JetBrains Mono 700)
- Profissão: `UX/UI Designer · Product Design`
- Slogan abaixo: *"Resolvendo problemas reais com design."*

## Botões de ação rápida (4)

- E-mail
- LinkedIn
- GitHub
- Calendly

Formato: botão quadrado com cantos suaves (8px), borda 1px azul-elétrico, fundo preto-azulado, ícone outline. Sem label embaixo — label vai no `aria-label`.

## Links customizados (3) — seção "// LINKS"

- Portfólio (pedro.design)
- Case studies em destaque
- Disponibilidade & rates

Cards com fundo `#16161D`, borda 1px azul-elétrico, raio 8px, ícone à esquerda + texto + seta `→` à direita.

## Detalhes visuais

- Raio: **8px**
- Modo: **escuro fixo**
- Sem sombras (estética flat dark tech)
- Pode incluir um cursor piscando (`_`) após algum texto, ou prompt `>` antes do título da seção

## Acabamento esperado

Sensação de portfólio dev/designer moderno, terminal-inspired, sóbrio e contemporâneo.
