# Aprendendo Python com o Gemini Notebook

Neste projeto, investiguei como o **Gemini Notebook** pode apoiar uma pessoa iniciante a organizar os estudos de Python a partir de fontes que selecionei.

## Pergunta central

> Como o Gemini Notebook pode ajudar um iniciante no aprendizado de Python?

## Objetivo

Usei o Gemini Notebook para reunir fontes sobre Python, testar diferentes formas de pedir apoio para os estudos e analisar criticamente as respostas geradas.

## Fontes selecionadas

Selecionei cinco fontes com papéis diferentes no processo:

1. Documentação oficial do Python — consulta técnica e referência da linguagem.
2. Curso em Vídeo: curso de Python — primeiros passos, lógica e exercícios.
3. *Pense em Python* — pensamento computacional e organização dos conceitos.
4. Python Brasil — comunidade e apoio ao aprendizado.
5. *3 projetos fáceis em Python* — exemplos práticos de projetos.

Os links e o registro das fontes estão em [`fontes/`](fontes/README.md).

## Experimentos com prompts

### Experimento 1 — sequência inicial de estudos

**Prompt utilizado**

> Estou começando a estudar Python e ainda tenho pouca experiência com programação. Com base nas fontes deste notebook, por onde devo começar meus estudos? Organize os principais conceitos em uma ordem de aprendizado, explique brevemente a importância de cada um e sugira uma forma prática de estudar cada etapa.

**Resultado observado:** recebi uma sequência ampla, que começava pela preparação do ambiente e avançava até projetos com interface gráfica.

**Cicatriz:** percebi que a resposta trouxe muitos assuntos e não resultava, por si só, em uma rotina prática de estudos. Por isso, tornei o pedido mais específico no experimento seguinte.

### Experimento 2 — plano de quatro semanas

**Prompt utilizado**

> Estou começando a estudar Python e tenho pouca experiência com programação. Com base exclusivamente nas fontes deste notebook, crie um plano de estudos para as primeiras 4 semanas. Organize os conteúdos do mais básico ao mais avançado, considerando que estudarei cerca de 1 hora por dia. Para cada semana, indique os principais conceitos que devo aprender, uma atividade prática para fixação e um pequeno projeto ao final. Use português do Brasil e evite incluir conteúdos que dependam de conhecimentos avançados.

**Resultado observado:** obtive um plano de quatro semanas, com variáveis, tipos de dados, operadores, strings, condicionais, listas e pequenas atividades práticas.

**Cicatriz:** constatei que indicar público, duração, período, idioma, atividades e limites de conteúdo tornou a resposta mais útil para o objetivo do experimento.

### Experimento 3 — conferência das fontes

**Prompt utilizado**

> Analise o plano de estudos que você criou e, para cada semana, indique quais das fontes do notebook sustentam os conceitos e exercícios recomendados. Não utilize informações externas às fontes. Quando uma recomendação não estiver claramente presente nas fontes, sinalize isso.

**Resultado observado:** o Gemini Notebook relacionou as recomendações às fontes e indicou quando uma adaptação não era literal. No caso do projeto Jokenpô, por exemplo, a fonte trabalhava com interface gráfica; a versão de terminal foi uma adaptação didática baseada na lógica do projeto.

**Cicatriz:** a verificação das fontes mostrou que uma resposta plausível ainda precisa ser revisada. A curadoria e a decisão final continuaram sendo minha responsabilidade durante o estudo.

## Materiais gerados

Durante o experimento, gerei no Gemini Notebook:

- mapa mental;
- apresentação em slides;
- podcast.

Os slides também revelaram um limite importante: alguns resultados deram destaque excessivo à fonte de projetos com interface gráfica, incluindo Tkinter e programação orientada a eventos. Essa observação reforçou para mim que as fontes selecionadas e a formulação do pedido influenciam o material gerado.

Os materiais que eu decidir publicar ficarão em [`resultados/`](resultados/README.md).

## Aprendizados

- O Gemini Notebook me ajudou a reunir, organizar e comparar informações das fontes.
- Prompts com contexto e restrições produziram respostas mais úteis para o meu objetivo.
- A ferramenta não substituiu minha revisão crítica: conferi o que estava realmente sustentado pelas fontes.
- O melhor resultado do experimento foi um plano de estudos mais organizado, não uma resposta pronta para ser seguida sem avaliação.

## Estrutura do repositório

```text
fontes/       # links ou registros das cinco fontes
prompts/      # registro dos prompts e das cicatrizes observadas
resultados/   # mapa mental, slides e podcast exportados
README.md     # visão geral do experimento
```

## Autoria

Este repositório registra meu experimento, desde a seleção das fontes e a elaboração dos prompts até a análise dos resultados gerados pelo Gemini Notebook.
