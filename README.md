# Portfólio · Nicoli Coelho

Portfólio pessoal — AI Builder · Produto, automação e IA generativa para negócios.

Site estático em HTML, CSS e JavaScript puros (sem build, sem dependências).

## Estrutura

```
index.html   → conteúdo do site
styles.css   → estilos (tema claro/escuro)
script.js    → menu mobile, tema, filtro de projetos e animações
favicon.svg  → ícone da aba
Curriculo_Nicoli_Coelho.pdf → currículo para download (substitua pelo arquivo novo, mantendo o nome)
```

## Rodar localmente

Abra o `index.html` no navegador, ou:

```bash
npx serve .
```

## Publicar na Vercel

1. Suba esta pasta para um repositório no GitHub.
2. Em [vercel.com/new](https://vercel.com/new), importe o repositório.
3. Framework Preset: **Other**. Deixe Build Command e Output Directory em branco.
4. Clique em **Deploy**.

## Editar o conteúdo

Todo o texto está no `index.html`, organizado por seções (`#sobre`, `#projetos`, `#trajetoria`, `#competencias`, `#contato`).
Para adicionar um projeto, copie um bloco `<article class="card">` e ajuste o atributo `data-tags`
(`produto`, `ia`, `automacao`) para que ele apareça nos filtros.
