📊 Regressão Linear - Análise da Cesta Básica no Brasil
Este projeto tem como objetivo aplicar técnicas de regressão linear para analisar a evolução dos preços da cesta básica em cidades brasileiras ao longo do tempo, com foco especial na cidade de Curitiba.

📁 Estrutura do Projeto
STP-20250506201022717.csv: Base de dados contendo os valores mensais da cesta básica em diversas capitais brasileiras.

notebook.ipynb: Código em Python desenvolvido no Google Colab para análise dos dados e aplicação do modelo de regressão.

README.md: Este arquivo com a descrição do projeto.

🛠️ Tecnologias Utilizadas
Python

Pandas

NumPy

Matplotlib

Scikit-learn

🔍 Etapas Realizadas
Leitura da base de dados com codificação adequada (latin1);

Limpeza e tratamento dos dados, incluindo separação correta das colunas e conversão de datas;

Extração de variáveis como ano e mês para uso como preditores;

Aplicação da regressão linear para prever o valor da cesta básica com base na passagem do tempo;

Visualização gráfica dos valores reais e da linha de tendência estimada.

📈 Resultado
O modelo de regressão linear permitiu identificar uma tendência nos valores da cesta básica ao longo dos meses e anos. O gráfico gerado mostra a evolução e a previsão com base no modelo.


🚀 Como Executar
Você pode abrir o notebook.ipynb diretamente no Google Colab ou em um ambiente Jupyter local. Certifique-se de ter os seguintes pacotes instalados:

bash
Copiar
Editar
pip install pandas numpy matplotlib scikit-learn
✍️ Autor
Projeto desenvolvido por Cleber Arthur de Oliveira Soares como parte dos estudos em Inteligência Artificial e Ciência de Dados.
