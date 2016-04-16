---
layout: page
title: Exemplos
permalink: /exemplos/
---

# Comece a explorar
Veja o que já conseguimos extrair sobre o Brasil, por exemplo. Aproveite para clicar em outras entidades relacionadas ao Brasil e explorar a interconectividade dos dados ligados extraídos da Wikipedia.

Você também pode executar consultas como se a enciclopédia fosse um banco de dados usando SPARQL, uma linguagem de consulta RDF que é parecida com o SQL. Por exemplo, para encontrar todos os presidentes que tem como religião o catolicismo, pode-se formular em SPARQL:

`SELECT DISTINCT ?presidente WHERE {
  ?presidente a dbpedia-owl:President .
  ?presidente dbpedia-owl:religion <http://pt.dbpedia.org/resource/Catolicismo> .
}`
	
Clique aqui para executar essa consulta e visualizar os resultados em uma tabela. Veja outros casos de uso, aplicações e informações gerais na página da DBpedia.org.

# Outros exemplos:

# Educação

Este é um pequeno exercício para demonstrar a utilidade do conceito de Dados Ligados (Linked Data) como base para o compartilhamento de dados (governamentais) abertos. 
Nosso caso de uso é o da avaliação do envolvimento de representantes do povo brasileiro na solução de problemas eminentes em sua região de origem. Tomamos como exemplo a educação, e buscamos políticos que vem de estados com alto índice de analfabetismo e que envolvem-se com projetos relacionados à educação. O índice de analfabetismo é extraído da Wikipedia pelo projeto DBpedia Portuguese, enquanto as votações de políticos são obtidas do projeto Ligado Nos Políticos. Você pode ver como esse exemplo foi executado a partir da página do exemplo.
