# ETL-FuncionariosDesativados
Processo de ETL básico, 

EXTRACT
os dados são extraidos de diferentes arquivos excel, 
02-2023.xlsx e 03-2023.xlsx referentes a uma relação de funcionarios desativados e suas respectivas empresas
RSG005_UsuarioEmpresa.xlsx arquivo retirado direto do sistema, onde foi feito alguns pre tratamentos apenas para que fsse possivel a leitura do arquivo sem erros.

TRANFORM
foram feitos alguns tratamentos como
 - Retirada de espaços nos campos, 
 - Exclusão de colunas extras, 
 - Unificação das tabelas referentes aos meses 02 e 03
 - Cruzamento das infromações das peimrias planilhas com a que foi retirada do sistema

LOAD
o resultado dos tratamentos e analises foi gerado em um novo arquivo excel output.xlsx
