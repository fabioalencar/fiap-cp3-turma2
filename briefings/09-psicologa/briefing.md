# Briefing 09 — Psicóloga Infantil

## Persona

**Dra. Ana Beatriz Moraes**, 38 anos, psicóloga infantil. Consultório em Belo Horizonte, MG. Atende crianças de 4 a 12 anos e orientação parental. Comunicação acolhedora.

## Paleta

- Primária (fundo): `#FDF6F0` (creme suave)
- Destaque: `#A8C6A1` (verde-sálvia)
- Acento: `#E8B4B8` (rosa-pó)

## Tipografia

- **Nunito** (Google Fonts) — pesos 400, 600, 800
- Nome em weight 800 (estética arredondada amigável)

<!-- gerado:fontes -->
### Google Fonts — copie e cole

No `<head>` do `index.html`, antes do `<link>` do seu `style.css`:

```html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Nunito:ital,wght@0,400;0,500;0,600;0,800;1,400&display=swap" rel="stylesheet">
```

No `style.css`, use a fonte com `font-family`:

```css
/* títulos e texto */
font-family: "Nunito", sans-serif;
```
<!-- /gerado:fontes -->

## Foto

- **Visível**, circular, 130×130px
- Fundo da foto pode ter um halo (anel sutil) na cor verde-sálvia

<!-- gerado:arquivos -->
## Arquivos que você recebe

Tudo está na pasta `assets/`, ao lado deste briefing. Copie a pasta inteira para dentro da sua entrega.

| Arquivo | Para quê |
|---|---|
| `assets/foto.png` | Foto da persona (512 × 512, quadrada). O formato e o tamanho pedidos acima são com CSS. |
| `assets/icons/whatsapp.svg` | Ícone do botão WhatsApp |
| `assets/icons/email.svg` | Ícone do botão E-mail |
| `assets/icons/phone.svg` | Ícone do botão Ligar |
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

- Nome: **Dra. Ana Beatriz Moraes**
- Profissão: `Psicóloga Infantil — CRP 04/12345`
- Slogan abaixo: *"Um espaço seguro para crescer."*

## Botões de ação rápida (4)

- WhatsApp
- E-mail
- Ligar
- Instagram

Formato: ícone preenchido verde-sálvia dentro de círculo rosa-pó claro, label embaixo em Nunito 600.

## Links customizados (3) — seção "Acolhimento"

- Como funciona a primeira sessão
- Atendimento online ou presencial
- Orientação parental

Botões com fundo branco, borda 1px verde-sálvia, raio **24px** (super arredondado), texto em verde-sálvia escuro.

## Detalhes visuais

- Raio: **24px** (visual macio, infantil-friendly)
- Modo: **claro fixo**
- Sombras suaves rosadas (`0 4px 16px rgba(232,180,184,0.25)`)
- Pode incluir 1-2 elementos decorativos arredondados (círculos pastel) no fundo

## Acabamento esperado

Sensação acolhedora, segura, adequada para famílias com crianças.
