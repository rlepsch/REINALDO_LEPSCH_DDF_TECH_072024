# REINALDO_LEPSCH_DDF_TECH_072024
Case Base de Tecnologia REINALDO LEPSCH NETO para DADOSFERA  
.  
## 0 - Sobre Agilidade e Planejamento  
.  

<img width="1130" alt="Screenshot 2024-07-25 at 14 27 00" src="https://github.com/user-attachments/assets/cd06e760-5089-48e9-8891-6f272b96d858">  
.  

.   
<img width="665" alt="Screenshot 2024-07-25 at 14 32 34" src="https://github.com/user-attachments/assets/d464d528-d075-4aa5-bd35-e92549b899ac">  
.  
## 1 - Sobre a Base de Dados  
.  
Base sugerida : https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024  
.  

<img width="638" alt="Screenshot 2024-07-25 at 15 14 00" src="https://github.com/user-attachments/assets/610d6252-22d9-4f00-a397-cd6ce2e31688">  
.  

## 2.1 - Sobre a Dadosfera - Integrar  
.  
<img width="1385" alt="Screenshot 2024-07-25 at 15 25 08" src="https://github.com/user-attachments/assets/68af740a-4247-4491-ac44-6ff670a5869f">  
.  
## 3 - Sobre a Dadosfera - Explorar  
.  
<img width="1443" alt="Screenshot 2024-07-25 at 15 44 32" src="https://github.com/user-attachments/assets/3dd020d7-015d-44e4-8e78-b1f18011118c">  
.  
## 4 - Sobre Data Quality  
.  
<img width="811" alt="Screenshot 2024-07-25 at 15 51 55" src="https://github.com/user-attachments/assets/f82c7168-eb8c-44a1-ab5d-b32c0893b157">  
.  
(detalhe em Rel Qualidade Dados.ipynb)  
.  
## 5 - Sobre o uso de GenAI e LLMs - Processar  
.  
(Foi utilizado o dataset de produtos sugerido, pois aquele que estou utilizando tem estrutura distinta. Usei somente as primeiras 10000 linhas para agilizar. O codigo para a transformação está em products.ipynd)  
.  
      docid                                              title  \
0         1  fyy leather case with mirror for samsung galax...   
1         2  playtex women's 18 hour easy on, easy off fron...   
2         4  yuepin u-tube clamp 304 stainless steel hose p...   
3         5            bruce's big storm (mother bruce series)   
4         6  dji shoulder neck strap belt sling lanyard nec...   
...     ...                                                ...   
9995  14926  rhino trunk & case camp & college trunk with r...   
9996  14929       ajax triple action orange(414ml) (pack of 3)   
9997  14930  tablet 10 inch android 10.0 yestel tablets 5g/...   
9998  14931  fse robline white whipping twine kit w/ needle...   
9999  14932  2pcs toothpaste whitening foam，citrus baking s...   

                                                   text  \
0     product description premium pu leather top qua...   
1     product description introducing playtex 18 hou...   
2     product description specification: material: 3...   
3      books children's books science, nature & how ...   
4     product description specifications: item condi...   
...                                                 ...   
9995  from the brand rhino trunk & case trunks for y...   
9996   health & household household supplies dishwas...   
9997  product description about yestel: thank you fo...   
9998  product description fse robline white whipping...   
9999  product description toothpaste sensitive teeth...   

                                               combined        00  000  0000  \
0     fyy leather case with mirror for samsung galax...  0.000000  0.0   0.0   
1     playtex women's 18 hour easy on, easy off fron...  0.000000  0.0   0.0   
2     yuepin u-tube clamp 304 stainless steel hose p...  0.000000  0.0   0.0   
3     bruce's big storm (mother bruce series)  books...  0.000000  0.0   0.0   
4     dji shoulder neck strap belt sling lanyard nec...  0.000000  0.0   0.0   
...                                                 ...       ...  ...   ...   
9995  rhino trunk & case camp & college trunk with r...  0.008966  0.0   0.0   
9996  ajax triple action orange(414ml) (pack of 3)  ...  0.000000  0.0   0.0   
9997  tablet 10 inch android 10.0 yestel tablets 5g/...  0.000000  0.0   0.0   
9998  fse robline white whipping twine kit w/ needle...  0.000000  0.0   0.0   
9999  2pcs toothpaste whitening foam，citrus baking s...  0.000000  0.0   0.0   

      00000  000000  000000000  ...  𝘀𝘁𝗮𝗶𝗻𝗹𝗲𝘀𝘀  𝘢𝘭𝘭  𝘢𝘳𝘦   𝘪𝘯   𝘰𝘧  𝘴𝘦𝘵  \
0       0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
1       0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
2       0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
3       0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
4       0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
...     ...     ...        ...  ...        ...  ...  ...  ...  ...  ...   
9995    0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
9996    0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
9997    0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
9998    0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   
9999    0.0     0.0        0.0  ...        0.0  0.0  0.0  0.0  0.0  0.0   

      𝘴𝘪𝘻𝘦𝘴   𝟭𝟲   𝟮𝟰  𝟯𝟭𝟲  
0       0.0  0.0  0.0  0.0  
1       0.0  0.0  0.0  0.0  
2       0.0  0.0  0.0  0.0  
3       0.0  0.0  0.0  0.0  
4       0.0  0.0  0.0  0.0  
...     ...  ...  ...  ...  
9995    0.0  0.0  0.0  0.0  
9996    0.0  0.0  0.0  0.0  
9997    0.0  0.0  0.0  0.0  
9998    0.0  0.0  0.0  0.0  
9999    0.0  0.0  0.0  0.0  

[10000 rows x 81749 columns]  


.  
.  
## 6 - Sobre Modelagem de Dados  
.  
Vamos trabalhar com a tabela de produtos, já que a que escolhi inicialmente (pensei que poderia escolher qq dataframe fora das sugestoes) nao oferece uma analise comercial muito rica.  
.  
Para este cenário, vamos utilizar a modelagem Dimensional de Kimball, pois ela é amplamente usada para Data Warehousing devido à sua simplicidade e eficiência para consultas analíticas. A modelagem dimensional é baseada na criação de tabelas fato e tabelas dimensão.  
.  
Cenário dos Dados e do Cliente  
.  
Dados: Temos um dataset de produtos com títulos e descrições.  
Cliente: Provavelmente uma empresa que deseja analisar produtos, identificar tendências, e entender melhor as características dos produtos mais vendidos.  
.  
Tabelas Fato e Dimensão  
.  
Tabela Fato: Contém os eventos ou transações, como vendas de produtos.  
Tabelas Dimensão: Contêm os atributos descritivos dos fatos, como informações sobre os produtos.  
.  
Estrutura das Tabelas  
.  
Tabela Fato: Fato_Vendas  
ID_Venda: Chave primária.  
Data_Venda: Data da venda.  
ID_Produto: Chave estrangeira referenciando a tabela Dim_Produto.  
Quantidade_Vendida: Quantidade de produtos vendidos.  
Valor_Venda: Valor total da venda.  
.  
Tabela Dimensão: Dim_Produto  
ID_Produto: Chave primária.  
Titulo_Produto: Título do produto.  
Descricao_Produto: Descrição do produto.  
Categoria_Produto: Categoria do produto (extraída das descrições ou fornecida externamente).  
Marca_Produto: Marca do produto (extraída das descrições ou fornecida externamente).  
.  
Tabela Dimensão: Dim_Data  
ID_Data: Chave primária.  
Data: Data completa.  
Ano: Ano.  
Mes: Mês.  
Dia: Dia.  
.  
Justificativa para a Modelagem Dimensional (Kimball)  
.  
A modelagem dimensional é escolhida por sua facilidade de uso e otimização para consultas analíticas. As tabelas fato centralizam os eventos principais (vendas), enquanto as tabelas dimensão fornecem contexto descritivo (informações sobre produtos e datas). Isso facilita a criação de relatórios e análises, permitindo uma visualização clara dos dados.  
.  
Visões Finais dos Dados  
.  
Visão 1: Análise de Vendas por Produto  
Objetivo: Identificar quais produtos estão vendendo mais, em quais períodos, e entender as tendências de vendas.  
Colunas:  
Data_Venda  
Titulo_Produto  
Quantidade_Vendida  
Valor_Venda  
Categoria_Produto  
Marca_Produto  
.  
Visão 2: Desempenho de Vendas por Categoria e Marca  
Objetivo: Analisar o desempenho de vendas por categoria de produto e por marca, ajudando a identificar quais categorias e marcas são mais lucrativas.  
Colunas:  
Data_Venda  
Categoria_Produto  
Marca_Produto  
Quantidade_Vendida  
Valor_Venda  
.  
Diagrama Representando as Camadas Finais do Data Warehouse Proposto  
.  
.  
+-------------------+          +------------------+          +-----------------+  
|   Dim_Produto     |          |     Fato_Vendas  |          |     Dim_Data    |  
+-------------------+          +------------------+          +-----------------+  
| ID_Produto (PK)   |---+   +--| ID_Venda (PK)    |          | ID_Data (PK)    |  
| Titulo_Produto    |   |   |  | Data_Venda       |<---------| Data            |  
| Descricao_Produto |   |   |  | ID_Produto (FK)  |          | Ano             |  
| Categoria_Produto |   +---|->| Quantidade_Vendida|         | Mes             |  
| Marca_Produto     |       |  | Valor_Venda      |          | Dia             |  
+-------------------+       |  +------------------+          +-----------------+  
                            |  
                            +-> Chaves Estrangeiras  
.  
.  
Conclusão  
.  
A modelagem dimensional de Kimball é adequada para o cenário descrito, pois facilita a análise de dados desestruturados, transformando-os em features úteis para a tomada de decisões. A estrutura proposta com tabelas fato e dimensão permite consultas eficientes e relatórios detalhados sobre o desempenho de vendas por produto, categoria e marca.
.  
## 7 - Sobre Análise de Dados - Analisar  
.  
.  

## 8 - Sobre Pipelines  
.  
.  
## 9 - Sobre Data Apps  
.  
.  
## 10 - Apresentação do Case  
.  
.  
