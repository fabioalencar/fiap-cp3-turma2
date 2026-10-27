# Briefing 03 — Eletricista

## Persona

**Rogério Alves**, 47 anos, eletricista autônomo. Atende residências e pequenos comércios em Guarulhos e região. Comunicação prática, direta, sem firulas.

## Paleta

- Primária (fundo): `#FFFFFF`
- Destaque: `#FFC400` (amarelo-alerta)
- Secundária: `#111111` (preto)

## Tipografia

- **Roboto Condensed** (Google Fonts) — pesos 400, 700
- Nome em UPPERCASE, weight 700

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:wght@400;500;600;700&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Roboto Condensed", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Não usar foto pessoal** — usar o **logotipo**: as iniciais `RA` dentro de um círculo amarelo (pronto em `assets/logo.png`), 120×120px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/logo.png` | Logotipo pronto (512 × 512, fundo transparente). Não precisa desenhar: só ajuste o tamanho com CSS. |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/map.svg` | Ícone do botão Mapa |

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

- Nome: **ROGÉRIO ALVES**
- Profissão: `Eletricista Residencial — 24h`
- Slogan abaixo: *"Atendimento de emergência em até 30 minutos."*

## Botões de ação rápida (4)

- Ligar (botão grande, destaque amarelo)
- WhatsApp
- E-mail
- Mapa (Como chegar)

Formato: botões retangulares com ícone à esquerda e label à direita.

## Links customizados (3) — seção "SERVIÇOS"

- Instalações elétricas residenciais
- Troca de quadro de luz
- Manutenção predial

Botões com fundo amarelo, texto preto bold, raio 4px.

## Detalhes visuais

- Raio: **4px** (cantos quase retos, estética industrial)
- Modo: **claro fixo**
- Sombras: duras, deslocadas (`4px 4px 0 #111`) nos botões principais — estilo "neo-brutalismo"
- Bordas pretas grossas (2px) em cards de serviço

## Acabamento esperado

Sensação prática, urgência, confiança de profissional experiente.
