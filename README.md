# Caderno do Estudante de Gastronomia

Site de apresentação do produto, com conteúdo próprio de Gastronomia e todas as seções do modelo visual de Física. O projeto de Física permanece intacto.

## Estrutura

- Abertura editorial com papel, fitas, fichas pastel e tipografia de caderno.
- Visão geral e catálogo visual de ambientes do caderno, sem links externos.
- Biblioteca de resumos aprofundados e flashcards de revisão.
- Exemplo de ficha técnica com fator de correção e custo por porção.
- Semana completa, preparação de avaliações e entregas, explicações por dia.
- Telas ilustrativas de biblioteca, leitura, revisão, planner, produção e pesquisa.
- Funcionalidades com exemplos preenchidos, percurso de formação e laboratório culinário.
- TCC, iniciação científica, estágio e continuidade acadêmica.
- Planos completos de oficinas para estágio, monitoria, treinamento e avaliação formativa.
- Benefícios, referências sem redirecionamento, FAQ, oferta e suporte.

No celular, as primeiras dez fichas e vinte respostas começam abertas. Os demais conteúdos continuam disponíveis na mesma página. A semana, os cartões de módulos e os planos de oficina são visíveis sem carrossel. O movimento reduzido é respeitado.

## Conteúdo e fontes

O repositório `sarasantoscontas-dotcom/caderno-gastronomia-acesso` foi consultado somente para leitura. Fontes de conteúdo do produto: `README.md`, `data.js`, `topic-expansions-a.js`, `flashcards.js` e `expansion-modules-a/b/c/d/e.js`. Os textos foram selecionados e organizados para a apresentação comercial. Fichas, semana, telas, planos de oficina e valores de custo são exemplos didáticos. Não são registros de alunos ou de uma operação real.

Consulta técnica complementar: Cartilha sobre Boas Práticas para Serviços de Alimentação da Anvisa; Guia Prático de Indicadores de Pré-preparo e Preparo dos Alimentos da UFV; material Ficha Técnica da iniciativa Da Cozinha à Mesa/Unicamp. A página não contém links de navegação para esses sites.

## Arquivos editáveis

- `index.html` e `404.html`: estrutura, catálogo, oficinas, exemplos e oferta.
- `assets/content.json`: conteúdos dos resumos e flashcards.
- `assets/presentation.json`: agenda, percurso, benefícios, FAQ e apresentações.
- `assets/app.js`: carregamento, renderização e controles de abertura.
- `assets/style.css`: identidade do modelo com ajustes de Gastronomia e responsividade.
- `assets/config.json`: preço e checkout.

## Checkout

Preço de apresentação: R$ 69,99. Checkout de Gastronomia: `https://pay.cakto.com.br/62ayqtc`. O link está configurado em `assets/config.json` e nos botões estáticos de `index.html` e `404.html`. Os botões abrem em nova aba, com texto branco sobre verde. Não é presumida taxa de plataforma. A configuração do site não altera o preço em plataformas externas.

## Build e publicação

`npm run build` copia a página e os assets para `dist/`. `npm run check` confere a sintaxe JavaScript. `npm start` serve o build local. O projeto não exige instalação de dependências. A configuração `vercel.json` está pronta para uma importação como site estático; associar este repositório a um projeto próprio de Gastronomia.

As fontes são carregadas pelo Google Fonts, com alternativas em CSS. Este é um site de apresentação; não implementa autenticação nem coleta de dados. Os ambientes editáveis descritos pertencem ao produto de acesso, que salva os registros no navegador utilizado.
