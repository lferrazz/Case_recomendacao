# Sistema de Recomendação de Produtos | NLP & Similaridade de Cosseno

Este projeto implementa um sistema de recomendação de produtos baseado em Processamento de Linguagem Natural (NLP) e similaridade de cosseno. Utilizando um dataset de produtos da Amazon do Kaggle, o modelo é capaz de sugerir itens similares com base em suas descrições.

🚀 Tecnologias Utilizadas
Python 🐍

Pandas & NumPy → Manipulação e análise de dados

Scikit-learn → Vetorização TF-IDF e cálculo de similaridade

Cosine Similarity → Comparação entre produtos

🔧 Como Funciona?
Pré-processamento: Os nomes dos produtos são vetorizados usando TF-IDF.

Cálculo de Similaridade: A matriz de similaridade é gerada com cosine_similarity.

Recomendações: Ao inserir um nome de produto, o sistema retorna os mais similares, ordenados pelos produtos com maior rating.

📌 Melhorias Futuras
Implementação de busca aproximada, permitindo recomendações sem precisar digitar o nome exato.

Otimização para lidar com datasets maiores e consultas mais rápidas.

📂 Quer testar? Clone o repositório e explore as recomendações!

