# Briefing 16 — Nutricionista

## Persona

**Dra. Camila Vieira**, 32 anos, nutricionista clínica. Consultório próprio em Pinheiros, SP. Foco em nutrição funcional e emagrecimento saudável. Comunicação leve, didática, baseada em ciência.

## Paleta

- Primária (fundo): `#F4F1E8` (creme natural)
- Destaque: `#3E5C3A` (verde-floresta)
- Acento: `#D08A4F` (laranja-cerâmica)

## Tipografia

- **DM Serif Display** (Google Fonts) para nome — weight 400
- **Inter** (Google Fonts) para texto — weight 400, 500, 600

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:wght@400&family=Inter:ital,wght@0,400;0,500;0,600;0,700;0,900;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos */
font-family: "DM Serif Display", serif;
/* texto */
font-family: "Inter", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 128×128px
- Borda 3px verde-floresta com leve espaço (4px de padding externo)

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
| `assets/icons/email.svg` | Ícone do botão E-mail |
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

- Nome: **Dra. Camila Vieira** (em DM Serif Display)
- Profissão: `Nutricionista Clínica — CRN-3 56789`
- Slogan abaixo: *"Nutrição funcional para o seu ritmo."*

## Botões de ação rápida (4)

- WhatsApp
- Ligar
- E-mail
- Instagram

Formato: ícone preenchido verde-floresta em fundo branco circular, label embaixo em Inter 500 verde-floresta escuro.

## Links customizados (4) — seção "Atendimento"

- Agendar consulta online
- Plano alimentar personalizado
- Receitas funcionais (blog)
- Convênios e valores

Botões com fundo branco, borda 1px verde-floresta, raio **12px**, ícone laranja-cerâmica à esquerda, texto verde-floresta escuro à direita, seta `→` no fim.

## Detalhes visuais

- Raio: **12px**
- Modo: **claro fixo**
- Sombras muito sutis (`0 2px 8px rgba(62,92,58,0.08)`)
- Header com leve textura de fundo (gradiente creme→creme mais claro) — opcional
- Footer simples centralizado com `© 2026 Dra. Camila Vieira`

## Acabamento esperado

Sensação natural-clínica, leve, profissional acessível. Equilíbrio entre seriedade médica e calor humano.
