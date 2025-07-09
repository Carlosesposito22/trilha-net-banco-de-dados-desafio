# Minha Jornada de Aprendizado e Aplicação Prática em SQL

Este README documenta uma série de consultas SQL desenvolvidas como parte de uma atividade prática em bootcamp. Através da manipulação de um banco de dados de filmes e atores, tive a oportunidade de **aprimorar minhas habilidades e aprofundar meu entendimento** sobre os conceitos fundamentais do SQL, aplicando-os diretamente na resolução de problemas e na extração de informações valiosas.

Minha evolução neste projeto foi marcada pela capacidade de traduzir requisitos em consultas eficientes, explorando desde seleções básicas até junções complexas, o que solidificou meu conhecimento na prática.

---

## Conceitos Fundamentais de SQL Abordados e Aplicados:

### 1. Seleção e Projeção de Dados (`SELECT`)

No início, concentrei-me em selecionar dados específicos, aprendendo a:

* **Projetar Colunas Essenciais:** Escolher apenas as colunas necessárias (`SELECT Nome, Ano FROM Filmes`), garantindo uma saída limpa e focada.
* **Visualizar Dados Completos:** Utilizar o asterisco (`SELECT * FROM Atores`) para uma inspeção rápida de todas as informações de uma tabela.

### 2. Filtragem Precisa de Dados (`WHERE`)

A cláusula `WHERE` foi crucial para refinar os resultados, onde explorei:

* **Condições Simples:** Filtrar registros com base em igualdade (`WHERE Nome = 'De Volta para o Futuro'`) ou comparações numéricas (`WHERE Ano > 2000`).
* **Múltiplas Condições (`AND`):** Combinar critérios para seleções mais complexas, como buscar filmes dentro de uma faixa de duração específica (`WHERE Duracao > 100 AND Duracao < 150`), o que demonstrou o poder de refinar resultados.

### 3. Organização e Ordenação de Dados (`ORDER BY`)

Apresentar os dados de forma legível e ordenada foi um passo importante, praticando a:

* **Classificação Ascendente/Descendente:** Organizar os resultados por uma ou mais colunas, tanto em ordem crescente (`ORDER BY Ano`) quanto decrescente (`ORDER BY Quantidade DESC`), facilitando a análise.

### 4. Agregação e Análise de Dados (`GROUP BY` e `COUNT`)

Aqui, aprofundei-me na capacidade do SQL de sumarizar informações:

* **Agrupamento Inteligente:** Utilizar `GROUP BY` para consolidar dados por categorias (como agrupar filmes por `Ano`), permitindo análises por subconjuntos.
* **Contagem de Registros:** Aplicar `COUNT()` para quantificar elementos dentro de cada grupo (`COUNT(Id) AS Quantidade`), o que me permitiu, por exemplo, descobrir quantos filmes foram lançados por ano.

### 5. Integração de Dados com Junções (`INNER JOIN`)

Este foi um dos conceitos mais impactantes, pois aprendi a combinar informações de diferentes tabelas, simulando cenários do mundo real:

* **Conectando Tabelas Relacionadas:** Empregar `INNER JOIN` para unir dados de tabelas como `Filmes`, `Generos` e `Atores` através de suas chaves relacionadas. Isso me permitiu responder a perguntas complexas, como "quais gêneros um filme tem?" ou "quem atuou em qual filme e em que papel?".
* **Utilização de Aliases:** Simplificar as consultas longas com o uso de **apelidos (aliases)** curtos para as tabelas (`Atores A`, `Filmes F`), tornando o código mais limpo e compreensível, uma prática essencial para queries complexas.

---

## Fim
Esta atividade foi fundamental para solidificar meu conhecimento em SQL. Através da aplicação prática de `SELECT`, `WHERE`, `ORDER BY`, `GROUP BY`, `COUNT` e, principalmente, as diversas formas de `JOIN`, sinto-me mais confiante em manipular e extrair insights de bancos de dados. A experiência de resolver problemas reais com SQL no bootcamp foi crucial para minha **evolução como profissional de dados**.
