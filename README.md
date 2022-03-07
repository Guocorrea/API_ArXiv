# API_ArXiv
  - API da Universidade de Cornell (ArXiv)
  - Projeto 3 do curso de formação em Data Analysis pela Iron Hack.
  - URL da apresentação no Tableau Public: 
    - https://public.tableau.com/app/profile/gustavo.ururahy.corr.a/viz/ArXiv/Histria1

Pontos obrigatórios do projeto:
  - Construir através de uma API ou Web Scraping um DataFrame com dados para análise
  - Criar um esquema no SQL para receber os dados da API
  - Acessar a API pelo Python, extrair os dados e armazená-los no SQL
  - Criar um engine para extrair os dados do SQL para o Python
  - Criar uma visualização dos resultados no Tableau e apresentar

# Fonte de Dados
  - https://arxiv.org/
 
# Tecnologia Utilizada
  - Python
  - PostgreSQL 
     - DBeaver
  - Tableau Public

# Introdução do Projeto:
  A API ArXiv, da Universidade de Cornell, é uma API que fornece informações sobre as publicações científicas no mundo. Na documentação da API consta as áreas do conhecimento que podem ser acessadas, assim buscamos artigos relacionados a estresse e epigenética dentro da categoria "Biologia Molecular Quantitativa".
  A epigenética é um campo relativamente novo da biologia molecular, assim, analisar as temáticas relacionadas ao tema pode nos mostrar o comportamento das publicações científicas frente a criação de novos paradigmas do conhecimento.
  
# Método:
  - Através da API ArXiv, utilizar  o python para acessar as publicações relacionadas a estresse e genética nos últimos 30 anos.
  - Armazenar as informações obtidas em um SCHEMA do SQL
  - Criar um engine para puxar as informações do SQL para o Python
  - Fazer uma análise do total de publicações por ano, as principais revistas científicas do período e os temas de cada artigo.
  - Criar uma apresentação no Tableau com os resultados e insights obtidos.
  
# Objetivos do Projeto:
  - Construir a evolução das publicações científicas relacionadas com genética e estresse nos últimos 30 anos.
  - Análise do comportamento científico frente a novas descobertas.

# Resultados:
  - Quando analisamos a curva das publicaçõe em estresse nos últimos 30 anos, percebemos que entre o ano de 2012 e 2013, houve um aumento de 45% no número de publicações no tema, o maior aumento do período.
  - As revistas de maior publicação são disparadas duas: a "Biopolymers and Cell" e a "Neuropharmacology", uma voltada para a área de estrutura celular e outra na área de fisiologia celular.
  - Percebemos que em 2012 a revista "Neuropharmacology" apresentou um aumento exponencial em suas publicações, enquanto que a "Biopolymers and Cell" apresentou um aumento exponencial 1 ano depois, em 2013.
  - Quando analisamos por palavra-chave, vemos comportamentos similares em diversas palavras chave, como: gene, genética do comportamento e epigenética.
  - Ao ampliarmos a análise, percebemos que em 2010 surge o primeiro artigo sobre metilação, um conceito que explica o mecanismo pelo qual a epigenética funciona.
  - Dois anos após o primeiro artigo que comprova a metilação, vemos um aumento exponencial em toda a cadeia de pesquisas relacionadas ao estresse.
  - A correlação entre Epigenética com Genética do Comportamento e Estresse que antes de 2010 era nula, em 2010 se torna altamente representativa, mostrando que a descoberta da metilação traz a epigenética como uma sub-área do conhecimento de temas mais abrangentes.
  
# Conclusões:
  - A análise pôde mostrar que a descoberta da metilação causou um aumento exponencial em diversos temas relacionados genética do estresse, além de oficializar a epigenética como uma nova área do conhecimento científico.

