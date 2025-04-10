# 1) Objetivo do projeto
O objetivo desse projeto de engenharia de dados é responder perguntas relacionadas a vendas de roupas no formato varejo. Deseja-se responder as questões abaixo:
- Qual foi o produto mais vendido em todo o período disponível para análise?
- Qual o mês com mais vendas do ano mais antigo?
- Qual cliente mais comprou no mês de abril do ano mais recente?
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
![Lógico_MVP1v1](https://github.com/user-attachments/assets/e3be351c-2e04-4c59-ac6d-9efbef23805c)

## 3.2) Catálogo de dados

## 3.3) Dicionário de dados

Tabela transações:
![image](https://github.com/user-attachments/assets/acca1df6-e1c3-4b7f-9d1b-914283c63a0a)

Tabela clientes:
![image](https://github.com/user-attachments/assets/6f3f151c-398a-4b55-894a-484fc3850322)

Tabela produtos:
![image](https://github.com/user-attachments/assets/3e61a1b9-a323-4991-a669-fb58c476d275)

Tabela funcionarios:
![image](https://github.com/user-attachments/assets/56862200-47be-4ee1-9515-e08885ffa3eb)

Tabela lojas:
![image](https://github.com/user-attachments/assets/ddddb4d0-449b-45a4-ac5d-52068a535f54)


# 4) Carga
## 4.1) Extração, transformação e carga

# 5) Análise
## 5.1) Qualidade dos dados
## 5.2) Respostas das questões levantadas

# 6) Autoavaliação
Inicialmente, pensou-se em usar dados da empresa em que trabalho para aproveitar o conhecimento do negócio relacionado ao conjunto de dados porém, não estava sendo um processo simples de ter a autorização. Desse modo, foi escolhido um tema de interesse e iniciada a busca no Kaggle, por ser conhecido amplamente pela quantidade de dados disponível para pessoas que querem aprender mais sobre análise e ciência de dados. Nesse contexto, entende-se que, é muito provável que quanto mais conhecimento do negócio se tem, melhores são as perguntas, que consequentemente trazem respostas melhores e análises com mais qualidade para o negócio. 
