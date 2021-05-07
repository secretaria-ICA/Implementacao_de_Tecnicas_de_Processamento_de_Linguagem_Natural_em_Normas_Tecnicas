# Implementação de Técnicas de Processmento de Linguagem Natural em Normas Técnicas 

### Aluno: José Eduardo Dias Junior
### Orientador: Leonardo Alfredo Forero Mendoza

## Resumo

Esse "notebook" aplica Processamento de Linguagem Natural a um conjunto restrito de textos: normas técnicas de engenharia da Petrobras, demonstrando diferentes aproximações e applicações.

Ele analisa arquivos em PDF, pre-processa e exporta seu conteúdo para um arquivo CSV, então o texo é tokenizado. 

Modelos Word2Vec e Doc2Vec são treinados com a ajuda da bibilioteca Gensin. O modelo pré-treinado GloVe também utilzado

Análise de componente principal é aplicada ao modelo Word2Vec é aplicada às versões em portugues e inglês dos documentos, provendo dicas visuais sobre o conteúdo dos documentos em ambas as línguas. 


Operações básicas utilizando os modelos vetoriais sao demonstradas:

  Coseno das distancias é utilizado para demonstrar a acurácia do modelo na identificação de palavras similares;
  A aplicação da ferramenta de matriz de tradução da Gensin entre os modelos Portugues - Ingles e Portugues - Glove;
  A função de similaridade de documentos como busca de termos nas normas. 
  
Recomendações futuras:
  
  Implementar interface para usuário da busca por similaridade Doc2Vec.



## Abstract
This notebook is applies Natural Language Processing Text Vetorization to a set of restricted corpora: thecnical engineering documents from Petrobras, demonstrating different aproachs and applications.

It parses pre-downloaded PDF files,  pre-process and saves the text into CSV files as a checkpoint. 

The text is tokenized and Word2vec and Doc2vec Gensim models are trained. The pre-trained GloVe model is also used 

Principal Component Analysis is applied to Word2Vec in equivalent text (Petrobras technical documents in Portuguese and English) providing visual cues for the documents contents in both languages.

Basic operations using the vector models are demonstrated:
  Cosine distance is used to demonstrate the accuracy of the model in identifying similar words;
  Gensim translation matrix is applied between the Portuguese-English and Portuguese-GloVe models;
  Doc2Vec similarly function is applied in documents search;
  
To Do:

Improve Doc2Vec similarly seach user interface.
