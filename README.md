# PLN-Analise_de_Sentimentos_Twitter
repositório para trabalho de PLN analise de sentimentos Desenvolvedores Luiz Rosa e Marcos Emiliano
Trabalho de Sentiment Analysis Twitter proposto pelo Dr. Professor Robson Bonidia que 
ministra aulas na Faculdade FATEC - Ourinhos, que tem relacão na matéria de PLN.
- Trabalho tem como desenvolvedores do Projeto Marcos Emiliano Luca Gonçalves e Luiz Carlos Aparecido Rosa
- 1° entrega do projeto de Web Scraping tendo 2 códigos
- 1° foram usados as bibliotecas pandas e a snscrape.modules.twitter, usados para a raspagem de comentários
- O código segue as boas praticas com comentários linha por linha
- foram raspados 2000 tweets com tema #politica
- No 2° foram usados as bibliotecas nltk, pandas, re, spacy, numpy, sklearn que faz o tratamento dos dados coletados, removendo 
- Sendo que alguns caracteres especiais precisavam ser removidos como:
- ?://(?:[a-zA-Z]|[0-9]|[$-_@.&+]|[!*\(\),]|(?:%[0-9a-fA-F][0-9a-fA-F]))+', ''
- [^\w\s]', ''
- <[^<>]*>', ''
- agradecimento especial para Zoumana Keita do medium.com

Library Pandas
Pandas é uma biblioteca Python de código aberto que permite o manuseio de dados tabulares ( ou seja, explorar, limpar e processar). O termo originou-se do termo econometrico " panel data" , portanto, PAN( el)-DA ( ta) -S . Iniciado por Wes McKinney em 2008 devido à necessidade de uma ferramenta de análise quantitativa poderosa e flexível, o pandas se tornou uma das bibliotecas Python mais populares. Possui uma comunidade extremamente ativa de colaboradores O Pandas é construído sobre duas bibliotecas principais do Python — matplotlib para visualização de dados e NumPy para operações matemáticas. O Pandas atua como um wrapper sobre essas bibliotecas, permitindo que você acesse muitos dos métodos do matplotlib e do NumPy com menos código. Por exemplo, o pandas .plot()combina vários métodos matplotlib em um único método, permitindo que você crie um gráfico em poucas linhas.

##
Library Snscrape
snscrape é um raspador para serviços de redes sociais (SNS). Ele extrai coisas como perfis de usuário, hashtags ou pesquisas e retorna os itens descobertos, por exemplo. as postagens relevantes.

Atualmente, os seguintes serviços são suportados:

Facebook: perfis de usuários, grupos e comunidades (também conhecidas como postagens de visitantes)
Instagram: perfis de usuários, hashtags e localizações
Mastodon: perfis de usuário e toots (single ou thread)
Reddit: usuários, subreddits e pesquisas (via Pushshift)
Telegrama: canais
Twitter: usuários, perfis de usuários, hashtags, pesquisas (tweets ao vivo, principais tweets e usuários), tweets (tópico único ou adjacente), postagens de lista, comunidades e tendências
VKontakte: perfis de usuário
Weibo (Sina Weibo): perfis de usuário
##
Library NLTK
NLTK é uma plataforma líder para a construção de programas Python para trabalhar com dados de linguagem humana. Ele fornece interfaces fáceis de usar para mais de 50 corpora e recursos lexicais , como WordNet, juntamente com um conjunto de bibliotecas de processamento de texto para classificação, tokenização, lematização, marcação, análise e raciocínio semântico, wrappers para bibliotecas NLP de força industrial, e um fórum de discussão ativo .

Graças a um guia prático que apresenta fundamentos de programação juntamente com tópicos de lingüística computacional, além de documentação API abrangente, o NLTK é adequado para linguistas, engenheiros, estudantes, educadores, pesquisadores e usuários da indústria. O NLTK está disponível para Windows, Mac OS X e Linux. O melhor de tudo é que o NLTK é um projeto gratuito, de código aberto e voltado para a comunidade.

O NLTK foi chamado de “uma ferramenta maravilhosa para ensinar e trabalhar em lingüística computacional usando Python” e “uma biblioteca incrível para brincar com a linguagem natural”.
Natural Language Processing with Python fornece uma introdução prática à programação para processamento de linguagem. Escrito pelos criadores do NLTK, ele orienta o leitor através dos fundamentos da escrita de programas em Python, trabalhando com corpora, categorizando texto, analisando a estrutura linguística e muito mais.

##
Library re (regex)
O Python vem com uma biblioteca interna chamada re , que permite lidar com as expressões regulares encontrando padrões em uma string ou conjunto de caracteres que em uma análise de texto e seria prejudicada. Existem muitas funcionalidades regex residindo no módulo como re.search().

##
Library Spacy
SpaCy é uma biblioteca para Processamento de Linguagem Natural que pode processar e “entender” grandes volumes de texto. O SpaCy faz isso por meio de uma variedade de recursos.

##
Library Numpy
NumPy é uma biblioteca de Python que ajudará na análise dos dados. É usado por indivíduos que lidam com ciência de dados. É uma biblioteca de álgebra linear que possui ligações com bibliotecas C tornando-a muito rápida da qual a maioria dos pacotes de ciência de dados, como SciPy (Scientific Python), Matplotlib e Scikit-learn dependem até certo ponto. Ele adiciona suporte para arrays e matrizes grandes e multidimensionais, juntamente com uma grande coleção de funções matemáticas de alto nível para operar nesses arrays.

##
Library Scikit Learn
Scikit Learn é uma biblioteca usada para realizar aprendizado de máquina em Python. O Scikit Learn é uma biblioteca de código aberto licenciada sob BSD e reutilizável em vários contextos, incentivando o uso acadêmico e comercial. Ele fornece uma variedade de algoritmos de aprendizado supervisionados e não supervisionados em Python. O Scikit Learn consiste em algoritmos e bibliotecas populares.




