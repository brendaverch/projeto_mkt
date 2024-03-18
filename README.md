<h1 align="center">Segmentação de Clientes</h1>

## :memo: Descrição

Este projeto tem como objetivo segmentar grupos com diferentes intenções de compra com base em dados bancários, permitindo à equipe de marketing oferecer o produto correto de acordo com o perfil do cliente. Os dados utilizados incluem informações como saldo, frequência de atualização do saldo, quantidade e frequência de compras, limite de crédito, entre outros.

Após o pré-processamento e a análise exploratória dos dados, o algoritmo K-means é aplicado para segmentar os clientes em diferentes grupos. Além disso, técnicas de redução de dimensionalidade, como PCA e autoencoders, são utilizadas para visualizar e entender melhor a distribuição dos clientes nos clusters.

## :books: Funcionalidades
* Segmentação de Clientes: O projeto permite segmentar os clientes em grupos com base em seus comportamentos de compra, ajudando a equipe de marketing a personalizar suas estratégias de vendas.
* Pré-processamento de Dados: Realiza o tratamento de dados ausentes e a normalização dos dados para prepará-los para análise e modelagem.
* Análise Exploratória de Dados: Visualiza a distribuição das variáveis e identifica padrões nos dados antes da aplicação dos algoritmos de clusterização.
* Modelagem com K-means: Utiliza o algoritmo K-means para agrupar os clientes em clusters com base em características semelhantes de compra.
* Redução de Dimensionalidade: Aplica técnicas como PCA e autoencoders para reduzir a dimensionalidade dos dados e visualizar a distribuição dos clientes nos clusters de forma mais eficiente.
* Avaliação e Interpretação dos Resultados: Avalia a qualidade dos clusters gerados e interpreta os resultados para fornecer insights úteis para a equipe de marketing.

## :wrench: Tecnologias utilizadas
* Análise de Dados:
  * Python
  * Pandas
  * NumPy
  * Seaborn
  * Matplotlib
* Pré-processamento e Modelagem:
  * Scikit-learn
  * Redução de Dimensionalidade:
  * PCA
  * Autoencoders
 
    ## :rocket: Rodando o projeto
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para iniciar o projeto:
* Clone o repositório para sua máquina local:
```
git clone https://github.com/brendaverch/Preco_Imoveis_SP.git
```
* Navegue até o diretório do projeto:
```
cd Preco_Imoveis_SP
```
* Certifique-se de que você possui as dependências necessárias instaladas. Você pode instalá-las executando:
```
pip install pandas numpy seaborn matplotlib shapely geopandas scikit-learn joblib
```
