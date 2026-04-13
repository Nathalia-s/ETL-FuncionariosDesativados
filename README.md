# ETL - Multiplas fontes
Processo de ETL básico que pode ser usado no dia a dia para tratamento e manipulação de multiplas planilhas excel.
O caso utilizado é referente a listagem de funcionarios desativados e suas respetivas lojas.

EXTRACT

Os dados são extraidos de diferentes arquivos excel, 
02-2023.xlsx e 03-2023.xlsx referentes a uma relação de funcionarios desativados e suas respectivas empresas.
Ja o  arquivo RSG005_UsuarioEmpresa.xlsx é retirado direto do sistema ERP, onde foi feito alguns pré tratamentos apenas para que fosse possivel a leitura do arquivo sem erros.

TRANFORM

Foram feitos alguns tratamentos como
 - Retirada de espaços nos campos, 
 - Exclusão de colunas extras, 
 - Unificação das tabelas referentes aos meses 02 e 03,
 - Cruzamento das informações das primerias planilhas com a que foi retirada do sistema.

LOAD

O resultado dos tratamentos e analises foram colocados em um novo arquivo excel output.xlsx
