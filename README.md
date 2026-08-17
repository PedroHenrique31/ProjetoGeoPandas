# Projeto de Visualização de Dados com GeoPandas

Este projeto foi criado, inicialmente, como uma forma de aprender e explorar o uso do **GeoPandas** para análise e visualização de dados geoespaciais. Ao mesmo tempo, pretendo que o projeto tenha uma utilidade social, disponibilizando análises e visualizações que possam ser úteis para compreender melhor a realidade socioeconômica do Distrito Federal.

## Sobre os dados

Até o momento, uma das partes mais difíceis do projeto tem sido justamente a obtenção de dados confiáveis, consistentes e suficientemente bem documentados.

Grande parte dos dados utilizados foi obtida no **Instituto de Pesquisa e Estatística do Distrito Federal (IPEDF)**. Embora a instituição disponibilize uma quantidade considerável de informações, o processo de localização, interpretação e utilização desses dados é, na minha experiência, bastante trabalhoso (uma bomba, não recomendo pra ninguém).

Não encontrei uma documentação centralizada que explique de forma clara como os dados podem ser obtidos ou consumidos por meio de APIs,  caso exista uma API pública destinada a esse fim. As informações também são disponibilizadas de maneira bastante dispersa e, em geral, aparecem em pelo menos dois formatos principais.

O primeiro são os **Anuários Estatísticos do Distrito Federal**, disponibilizados em PDF e também em versões resumidas. O problema é que o conteúdo dos anuários varia de uma edição para outra, de acordo com os temas e necessidades abordados em cada publicação. Isso dificulta a construção de séries históricas consistentes.

O segundo formato são os **arquivos XLSX**, que em princípio seriam mais adequados para análises quantitativas, por apresentarem os dados de forma mais estruturada e categorizada. Entretanto, também existem dificuldades de padronização entre diferentes edições. Variáveis semelhantes podem aparecer com definições diferentes ao longo dos anos ou deixar de ser publicadas.

Por exemplo, em determinados conjuntos de dados é possível encontrar informações sobre **renda média por pessoa**, enquanto em outros a renda é apresentada por **família ou domicílio**. Há também indicadores que aparecem em algumas edições e deixam de ser disponibilizados posteriormente, como estimativas relacionadas ao número médio de pessoas por domicílio. O mesmo problema ocorre com indicadores como o **índice de Gini**, entre outros.

Além disso, não há uma documentação única que permita identificar facilmente:

* qual tabela deve ser utilizada para cada indicador;
* qual é exatamente a definição de cada variável;
* qual unidade de análise está sendo utilizada (pessoa, família ou domicílio, por exemplo);
* qual é a periodicidade de coleta ou publicação;
* quais metodologias foram utilizadas;
* e como as diferentes edições podem ser comparadas ao longo do tempo.

Essa falta de padronização e documentação torna a etapa de preparação dos dados consideravelmente mais complexa. Também limita análises mais aprofundadas, especialmente quando o objetivo é combinar diferentes indicadores para tentar compreender questões como **renda, desigualdade, composição familiar e custo de vida** no Distrito Federal.

Por isso, parte importante deste projeto não será apenas aprender a utilizar o GeoPandas, mas também documentar o processo de obtenção, tratamento e interpretação dos dados utilizados nas análises.

## Considerações finais

Apesar dessas dificuldades, espero que este trabalho possa ser útil, ainda que de forma modesta, para quem tiver interesse em explorar ou compreender melhor esses dados no futuro. Estou publicando o projeto no GitHub também com o objetivo de torná-lo aberto a contribuições: sugestões de fontes, correções, metodologias ou informações mais bem documentadas serão muito bem-vindas.

A ideia é que, com o tempo, o projeto possa não apenas evoluir tecnicamente, mas também construir uma base de dados mais consistente e útil para análises sobre a realidade socioeconômica do Distrito Federal.

