# Briefing 08 — Mecânico

## Persona

**Wagner Pires**, 49 anos, mecânico. Oficina própria especializada em carros nacionais e injeção eletrônica. Atende em Osasco, SP. Confiável, bom humor, tradicional.

## Paleta

- Primária (fundo): `#1A1A1A` (preto-grafite)
- Destaque: `#D62828` (vermelho oficina)
- Neutra: `#F2F2F2` (cinza-claro)

## Tipografia

- **Oswald** (Google Fonts) para títulos — weight 700, uppercase
- **Roboto** (Google Fonts) para texto — weight 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Oswald:wght@400;700&family=Roboto:wght@400;500;600;700&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Oswald", sans-serif;
/* texto */
font-family: "Roboto", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Não usar foto pessoal** — usar o **logotipo** da oficina: `WP` e "MECÂNICA" dentro de um círculo vermelho (pronto em `assets/logo.png`), 130×130px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/logo.png` | Logotipo pronto (512 × 512, fundo transparente). Não precisa desenhar: só ajuste o tamanho com CSS. |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/map.svg` | Ícone do botão Mapa |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="tel:+5511999999999">
  <img src="assets/icons/phone.svg" alt="" width="22" height="22">
  <span>Ligar</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome (em Oswald uppercase): **WAGNER PIRES**
- Profissão: `WP MECÂNICA — DESDE 1998`
- Slogan abaixo: *"Diagnóstico honesto. Conserto certo."*

## Botões de ação rápida (4)

- Ligar
- WhatsApp
- Mapa (Como chegar)
- E-mail

Formato: botões retangulares grandes, fundo vermelho, ícone à esquerda, texto à direita em uppercase Oswald branco.

## Links customizados (3) — seção "SERVIÇOS"

- Revisão completa
- Injeção eletrônica
- Mecânica geral

Cards com fundo cinza-escuro (`#262626`), borda esquerda 4px vermelha, raio **6px**.

## Detalhes visuais

- Raio: **6px**
- Modo: **escuro fixo**
- Linhas diagonais/listras (CSS gradient) como detalhe no header — estilo "fita de atenção"
- Sem sombras suaves; visual sólido e funcional

## Acabamento esperado

Sensação de oficina mecânica profissional, robusto, masculino, tradicional.
