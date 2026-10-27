# Briefing 07 — Arquiteta de Interiores

## Persona

**Camila Reis**, 36 anos, arquiteta de interiores. Escritório próprio em Florianópolis, SC. Projetos residenciais de alto padrão. Estética minimalista escandinava.

## Paleta

- Primária (fundo): `#F5F1EB` (off-white quente)
- Destaque: `#3A352F` (marrom-preto)
- Acento: `#9C8B73` (terroso)

## Tipografia

- **Manrope** (Google Fonts) para tudo — pesos 300, 500, 700
- Nome em weight 300 (light) — estética sofisticada minimalista

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Manrope:wght@300;400;500;600;700&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Manrope", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 110×110px (menor que o usual — sobriedade)
- Sem borda

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/instagram.svg` | Ícone do botão Instagram |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |

Os ícones já vêm na cor do cartão: use com `<img>`, sem editar o SVG.

```html
<a href="https://instagram.com/perfil">
  <img src="assets/icons/instagram.svg" alt="Instagram" width="22" height="22">
</a>
```

Os botões deste cartão não mostram texto: o nome de cada botão vai no `alt` do ícone.
<!-- /gerado:arquivos -->

## Cabeçalho

- Nome: **Camila Reis** (em weight 300)
- Profissão: `arquitetura · interiores · curadoria`
- Slogan abaixo: *"Espaços que respiram."*

## Botões de ação rápida (3)

- Instagram
- E-mail
- WhatsApp

Formato: apenas ícones em outline (sem fundo), 1px de stroke, em marrom-preto.

## Links customizados (4) — seção "Projetos"

- Portfólio residencial
- Projetos comerciais
- Processo de trabalho
- Solicitar orçamento

Botões sem fundo, apenas linha divisória inferior 1px terrosa entre eles, raio **0px** (mas sem aparência de "botão" — mais como itens de lista).

## Detalhes visuais

- Raio: **0px** (visual editorial)
- Modo: **claro fixo**
- Sem sombras
- MUITO espaço em branco (padding generoso, ar entre elementos)
- Tipografia em destaque (hierarquia tipográfica forte)

## Acabamento esperado

Sensação de revista de arquitetura, sofisticação silenciosa, curadoria.
