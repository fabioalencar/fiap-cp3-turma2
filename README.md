# Checkpoint 3 — Cartão de visita digital

**Vale 10 pontos.** Prova em sala, individual, **1h30**. Data: **03/11/2026** (terça-feira)

## Do que se trata

Você vai construir um **cartão de visita digital**: um mini-site de uma página, feito para celular, que apresenta um profissional. Pense no link que vai na bio do Instagram: foto (ou logo), nome, profissão, botões de contato rápido (WhatsApp, ligar, e-mail…) e uma lista de links.

Cada aluno recebe um **briefing** diferente, como se um cliente tivesse contratado você: uma confeiteira, um eletricista, uma sommelier, um DJ… O briefing diz as cores, as fontes, o formato da foto, os botões e os links. A sua parte é transformar isso em HTML e CSS.

O checkpoint junta o que vimos no semestre:

- **HTML semântico:** `header`, `main`, `nav`, `section`, `footer`, títulos, links e imagens com `alt`
- **CSS:** cores, fontes do Google Fonts, bordas, raios, sombras
- **Layout com flexbox e grid**, com `gap`
- **Pseudo-classes:** `:hover` e `:focus-visible`
- **Mobile first:** o cartão é pensado para a tela do celular

Foto, logo e ícones já vêm prontos. Você não precisa procurar imagem nem desenhar nada.

## Passo a passo

1. Ache o seu RM na tabela abaixo (em ordem crescente). O número ao lado é o seu briefing.
2. Baixe o zip do seu briefing (abra o link e clique em **Download raw file**).
3. Leia o `briefing.md` e olhe a `referencia.png`.
4. Monte o cartão em `index.html` + `style.css`.
5. Valide, zipe e entregue pelo Teams.

## Qual é o seu briefing

| RM | Briefing | Profissão | Zip |
|---|---|---|---|
| 573464 | [09](briefings/09-psicologa/) | Psicóloga Infantil | [09-psicologa.zip](pacotes/09-psicologa.zip) |
| 574299 | [24](briefings/24-pet-sitter/) | Pet Sitter / Dog Walker | [24-pet-sitter.zip](pacotes/24-pet-sitter.zip) |
| 574498 | [17](briefings/17-ux-designer/) | UX/UI Designer | [17-ux-designer.zip](pacotes/17-ux-designer.zip) |
| 574620 | [19](briefings/19-professora-yoga/) | Professora de Yoga | [19-professora-yoga.zip](pacotes/19-professora-yoga.zip) |
| 574728 | [20](briefings/20-maquiadora/) | Maquiadora Profissional | [20-maquiadora.zip](pacotes/20-maquiadora.zip) |
| 574739 | [22](briefings/22-florista/) | Florista | [22-florista.zip](pacotes/22-florista.zip) |
| 574750 | [08](briefings/08-mecanico/) | Mecânico | [08-mecanico.zip](pacotes/08-mecanico.zip) |
| 574803 | [05](briefings/05-advogado/) | Advogado Tributarista | [05-advogado.zip](pacotes/05-advogado.zip) |
| 575113 | [03](briefings/03-eletricista/) | Eletricista | [03-eletricista.zip](pacotes/03-eletricista.zip) |
| 575349 | [27](briefings/27-sommelier/) | Sommelier | [27-sommelier.zip](pacotes/27-sommelier.zip) |
| 575371 | [18](briefings/18-coach-financeiro/) | Coach Financeiro | [18-coach-financeiro.zip](pacotes/18-coach-financeiro.zip) |
| 575447 | [01](briefings/01-personal-trainer/) | Personal Trainer | [01-personal-trainer.zip](pacotes/01-personal-trainer.zip) |
| 575499 | [28](briefings/28-podcaster/) | Podcaster | [28-podcaster.zip](pacotes/28-podcaster.zip) |
| 575508 | [11](briefings/11-fotografo/) | Fotógrafo de Casamento | [11-fotografo.zip](pacotes/11-fotografo.zip) |
| 575525 | [16](briefings/16-nutricionista/) | Nutricionista | [16-nutricionista.zip](pacotes/16-nutricionista.zip) |
| 575813 | [07](briefings/07-arquiteta/) | Arquiteta de Interiores | [07-arquiteta.zip](pacotes/07-arquiteta.zip) |
| 575901 | [23](briefings/23-streamer/) | Streamer / Criador de Conteúdo Gamer | [23-streamer.zip](pacotes/23-streamer.zip) |
| 575926 | [14](briefings/14-veterinario/) | Veterinário | [14-veterinario.zip](pacotes/14-veterinario.zip) |
| 575957 | [04](briefings/04-confeiteira/) | Confeiteira | [04-confeiteira.zip](pacotes/04-confeiteira.zip) |
| 576025 | [15](briefings/15-tatuador/) | Tatuador | [15-tatuador.zip](pacotes/15-tatuador.zip) |
| 576103 | [26](briefings/26-professora-ingles/) | Professora de inglês | [26-professora-ingles.zip](pacotes/26-professora-ingles.zip) |
| 576188 | [12](briefings/12-barbeiro/) | Barbearia | [12-barbeiro.zip](pacotes/12-barbeiro.zip) |
| 576294 | [10](briefings/10-chef/) | Chef de Cozinha Italiana | [10-chef.zip](pacotes/10-chef.zip) |
| 576304 | [02](briefings/02-dermatologista/) | Dermatologista | [02-dermatologista.zip](pacotes/02-dermatologista.zip) |
| 576354 | [21](briefings/21-corretor-imoveis/) | Corretor de Imóveis | [21-corretor-imoveis.zip](pacotes/21-corretor-imoveis.zip) |
| 576450 | [13](briefings/13-nail-designer/) | Nail Designer | [13-nail-designer.zip](pacotes/13-nail-designer.zip) |
| 576451 | [06](briefings/06-dj/) | DJ / Produtor Musical | [06-dj.zip](pacotes/06-dj.zip) |
| 576922 | [25](briefings/25-fisioterapeuta/) | Fisioterapeuta esportivo | [25-fisioterapeuta.zip](pacotes/25-fisioterapeuta.zip) |

## O que vem no zip

```
NN-profissao/
├── briefing.md       ← a especificação: paleta, fontes, foto, botões, links, detalhes
├── referencia.png    ← como o cartão deve ficar no celular (375px)
└── assets/
    ├── foto.png      ← ou logo.png: já pronto, só aplicar forma e tamanho com CSS
    └── icons/        ← ícones em SVG, já na cor do seu cartão
```

O `briefing.md` traz o **código do Google Fonts pronto para copiar e colar** e a lista dos arquivos de `assets/`, com um exemplo de uso. Abra no VS Code com a visualização de Markdown (`Cmd/Ctrl + Shift + V`).

## Regras

- **HTML + CSS puro.** Sem framework (Bootstrap, Tailwind), sem JavaScript.
- **Celular primeiro:** o cartão é feito para uns 375px de largura. Teste no DevTools em modo dispositivo, em 320, 375 e 414px.
- **Use os arquivos do `assets/`.** Não troque a foto nem desenhe o logo.
- **Os textos são os do briefing** (nome, profissão, slogan, botões e links).
- **Sem IA generativa** (Copilot, ChatGPT, Claude, Cursor…). Desative antes de começar.
- Pode consultar MDN e as suas anotações.
- Não precisa de media query, variáveis CSS nem `position`: flexbox, grid e pseudo-classes resolvem tudo. Se quiser usar, pode.
- Na dúvida entre o briefing e a referência, **siga o briefing**.

## Sugestão de tempo

| Tempo | Etapa |
|---|---|
| 0:00–0:10 | Ler o briefing e olhar a referência |
| 0:10–0:35 | HTML semântico completo, com fontes, foto e ícones |
| 0:35–1:00 | CSS: página, cartão, cabeçalho, botões, links |
| 1:00–1:20 | Cores e detalhes do briefing, `:hover` e `:focus-visible`, teste em 320/375/414 |
| 1:20–1:30 | Conferir com o briefing, validar e entregar |

## Critérios (10 pontos)

| Pontos | Critério |
|---|---|
| 3,0 | **Fidelidade ao briefing:** cores, fontes, foto/logo (forma, tamanho, borda), botões e links completos, raios, sombras, claro/escuro |
| 2,0 | **Layout mobile:** cartão centralizado, botões em grid/flex com `gap`, links em largura total; 320/375/414 sem rolagem para o lado |
| 2,0 | **HTML semântico e válido:** `header`, `main`, `nav`, `section`, `footer`; um `h1`; links com `href` (`tel:`, `mailto:`, `https://wa.me/`); sem erros no [validator.w3.org](https://validator.w3.org/) |
| 1,0 | **Hierarquia e espaçamento:** nome em destaque, blocos separados com ritmo |
| 1,0 | **Estados:** `:hover` e `:focus-visible` em todos os botões e links |
| 1,0 | **CSS válido e organizado:** sem erros no [jigsaw.w3.org/css-validator](https://jigsaw.w3.org/css-validator/), sem `style=""` e sem `!important` |

## Entrega

Pasta com seu nome, zipada:

```
nome-sobrenome/
├── index.html
├── style.css
└── assets/          ← a pasta que você recebeu
```

No topo do `style.css`, um comentário com nome, RM e número do briefing. Envie pelo Teams **antes do fim do horário**. [Canal e horário: preencher]

Quando o briefing deixar uma dúvida de interpretação, decida você: você é o designer do projeto.

## Para treinar antes da prova

- **Aula de revisão:** o briefing da demo está em [`revisao/demo/`](revisao/demo/) (Rita Moura, ceramista), com referência e assets. Dá para acompanhar a aula montando junto.
- **Todos os briefings estão neste repositório.** Escolha um que não seja o seu e tente montar em 1h30, cronometrando.
