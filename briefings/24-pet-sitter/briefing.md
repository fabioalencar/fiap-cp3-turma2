# Briefing 24 — Pet Sitter / Dog Walker

## Persona

**Lia Marchetti**, 27 anos, pet sitter e dog walker. Atende bairros nobres de São Paulo (Jardins, Pinheiros, Vila Madalena). Comunicação alegre, confiável, ama bichos.

## Paleta

- Primária (fundo): `#FFF9F0` (creme alegre)
- Destaque: `#F59E0B` (amarelo-mostarda quente)
- Acento: `#EF6F6C` (coral suave)

## Tipografia

- **Fredoka** (Google Fonts) para nome e títulos — weight 500, 700 (arredondada, amigável)
- **Inter** (Google Fonts) para texto — weight 400, 500

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;700&family=Inter:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "Fredoka", sans-serif;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 130×130px
- Borda 3px amarelo-mostarda

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
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

- Nome: **Lia Marchetti**
- Profissão: `Pet Sitter & Dog Walker · Jardins/SP`
- Slogan abaixo: *"Seu pet em boas mãos quando você não pode estar."*

## Botões de ação rápida (4)

- WhatsApp
- Instagram
- E-mail
- Mapa (área atendida)

Formato: ícone preenchido branco dentro de círculo amarelo-mostarda, label embaixo em Fredoka 500 amarelo escuro.

## Links customizados (4) — seção "Serviços"

- Passeio individual (1h)
- Pet sitting noturno
- Cuidados durante viagem
- Reserve um horário

Botões com fundo branco, sem borda, raio **22px** (super arredondado), sombra suave coral, ícone coral à esquerda, texto amarelo-mostarda escuro.

## Detalhes visuais

- Raio: **22px** (visual super macio e amigável)
- Modo: **claro fixo**
- Sombras suaves coral (`0 4px 16px rgba(239,111,108,0.18)`)
- Uma patinha (`assets/icons/pata.svg`) acima da foto como ornamento
- Tipografia arredondada e generosa

## Acabamento esperado

Sensação alegre, pet-friendly, confiança gentil, vibe app de bairro.
