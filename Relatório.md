# 1) Objetivo do projeto
O objetivo desse projeto de engenharia de dados é responder perguntas relacionadas a vendas de roupas no formato varejo. Deseja-se responder as questões abaixo:
- Qual o mês com mais vendas no ano?
- E o mês com menos vendas?
- Qual produto é mais vendido em um ano?
- Os produtos com mais vendas no mês são os produtos com maior taxa de desconto?
- O mês com mais venda é o mês com maior incidência de desconto?

# 2) Coleta
## 2.1) Busca pelos dados
Iniciou-se o processo de busca pelo conjunto de dados no site www.kaggle.com.br, uma comunidade voltada para o aprendizado em ciência de dados. O conjunto de dados escolhido foi no tema de venda de roupas no setor varejo, disponível no link a seguir: https://www.kaggle.com/datasets/ricgomes/global-fashion-retail-stores-dataset 
## 2.2) Coleta dos dados
Segundo a plataforma Kaggle, o conjunto de dados escolhido está na versão bronze e tem 6 arquivos em .csv. Foi escolhido um conjunto com mais de um arquivo para intensificar a prática da modelagem com o modelo estrela.
Os dados simulam 2 anos de vendas de uma empresa multinacional de venda de roupas, totalizando 1GB de tamanho.
![image](https://github.com/user-attachments/assets/98618ccf-0961-4b5b-9627-0098b327289d)

Os arquivos foram baixados para o computador local para ser feito o upload no Community Databricks, plataforma sugerida e escolhida para produzir o projeto MVP.
O processo de upload no Community Databricks é iniciado com os comandos + New -> Add or upload data no canto superior esquerdo da plataforma.
![image](https://github.com/user-attachments/assets/26f32398-8668-4583-b02a-8d62d6d92e19)

Os 6 arquivos são escolhidos para serem carregados e salvos na pasta "global_fashion" para melhor organização no diretório DBFS. São eles: clientes.csv, descontos.csv, empregados.csv, produtos.csv, lojas.csv e transacoes.csv 
![image](https://github.com/user-attachments/assets/75825eff-96a5-473b-9fb2-046293e1fe6e)


Com isso, todos os dados necessários já estão no Databricks para iniciar o projeto no notebook.

# 3) Modelagem
## 3.1) Modelo estrela

## 3.2) Catálogo de dados

# 4) Carga
## 4.1) Extração, transformação e carga

# 5) Análise
## 5.1) Qualidade dos dados
## 5.2) Respostas das questões levantadas

# 6) Autoavaliação
Inicialmente, pensou-se em usar dados da empresa em que trabalho para aproveitar o conhecimento do negócio relacionado ao conjunto de dados porém, não estava sendo um processo simples de ter a autorização. Desse modo, foi escolhido um tema de interesse e iniciada a busca no Kaggle, por ser conhecido amplamente pela quantidade de dados disponível para pessoas que querem aprender mais sobre análise e ciência de dados. Nesse contexto, entende-se que, é muito provável que quanto mais conhecimento do negócio se tem, melhores são as perguntas, que consequentemente trazem respostas melhores e análises com mais qualidade para o negócio. 
