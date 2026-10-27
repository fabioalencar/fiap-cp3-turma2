# Briefing 28 — Podcaster

## Persona

**Joana Prates**, 29 anos, apresentadora e produtora do podcast **Ondas Paralelas**, gravado em Belo Horizonte, MG. Episódios longos de entrevista sobre cidades, música e as pessoas que fazem as duas coisas.

## Paleta

- Primária (fundo): `#121212` (grafite quase preto)
- Destaque: `#FF6B2C` (laranja-sinal)
- Acento: `#FFD23F` (amarelo)

## Tipografia

- **Archivo** (Google Fonts) — pesos 400, 600, 800
- Nome em weight 800, uppercase

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Archivo:wght@400;500;600;700;800&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Archivo", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Não usar foto pessoal** — usar o **logotipo** do podcast: monograma `OP` em Archivo, preto, dentro de um círculo laranja-sinal (pronto em `assets/logo.png`)
- 124 × 124px

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/logo.png` | Logotipo pronto (512 × 512, fundo transparente). Não precisa desenhar: só ajuste o tamanho com CSS. |
| `assets/icons/spotify.svg` | Ícone do botão Spotify |
| `assets/icons/youtube.svg` | Ícone do botão YouTube |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://open.spotify.com/">
  <img src="assets/icons/spotify.svg" alt="" width="22" height="22">
  <span>Spotify</span>
</a>
```

O texto do botão já diz o que ele faz, então o `alt` do ícone fica vazio (`alt=""`).
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **JOANA PRATES** (Archivo 800 uppercase)
- Profissão: `PODCAST ONDAS PARALELAS` (uppercase, letter-spacing, laranja)
- Slogan: *"Conversas longas sobre cidades, música e gente."*

## Botões de ação rápida (4)

- Spotify
- YouTube
- Instagram
- E-mail

Formato: ícone amarelo dentro de quadrado grafite com cantos de 8px e borda fina laranja, label embaixo em amarelo, uppercase, weight 700.

## Links customizados (4) — seção "EPISÓDIOS"

- Ep. 42 — A cidade à noite
- Ep. 41 — Discos que mudaram tudo
- Apoie o podcast
- Mídia kit (PDF)

Botões largura total, fundo laranja-sinal, texto grafite em uppercase weight 700, raio **6px**, seta `→` grafite à direita.

## Detalhes visuais

- Raio: **6px**
- Modo: **escuro fixo**
- Sem sombras
- Footer com `© 2026 Joana Prates`

## Acabamento esperado

Estúdio de rádio independente: escuro, direto, com o laranja e o amarelo fazendo barulho.
