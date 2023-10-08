<div align="center">
<img src="https://hermes.digitalinnovation.one/assets/diome/logo-full.svg" alt="Logo Bootcamp" width="140" align="right">
<h1>Santander Bootcamp 2023 <br> Ciência de Dados com Python</h1>
<img src="https://hermes.dio.me/tracks/03253ff0-95b9-4904-84e7-2063e9d6cb26.png" alt="Logo Bootcamp" width="220">
</div>

##  :brain: Desafio de projeto DIO: Processando e Transformando Dados com Power BI
O desafio desse projeto era concluir todo processo de ETL (Extract, Transform and Load) no Power Bi Desktop através do Power Query!
Ah! e conectar ao Banco de Dados da Azure, onde criamos nossa database e com o auxilio do Cloud Shell criamos nossas tabelas!
</a>

## :rocket: Entendendo o desafio
O Aluno deveria realizar as seguintes alterações e relações nas tabelas:<br>
<OL>

1. Criação de uma instância na Azure para MySQL

2. Criar o Banco de dados com base disponível no github

3. Integração do Power BI com MySQL no Azure

4. Verificar problemas na base a fim de realizar a transformação dos dados

Diretrizes para transformação dos dados

1. Verifique os cabeçalhos e tipos de dados

2. Modifique os valores monetários para o tipo double preciso

3. Verifique a existência dos nulos e analise a remoção

4. Os employees com nulos em Super_ssn podem ser os gerentes. Verifique se há algum colaborador sem gerente

5. Verifique se há algum departamento sem gerente

6. Se houver departamento sem gerente, suponha que você possui os dados e preencha as lacunas

7. Verifique o número de horas dos projetos

8. Separar colunas complexas

9. Mesclar consultas employee e departament para criar uma tabela employee com o nome dos departamentos associados aos colaboradores. A mescla terá como base a tabela employee. Fique atento, essa informação influencia no tipo de junção

10. Neste processo elimine as colunas desnecessárias.

11. Realize a junção dos colaboradores e respectivos nomes dos gerentes . Isso pode ser feito com consulta SQL ou pela mescla de tabelas com Power BI. Caso utilize SQL, especifique no README a query utilizada no processo.

12. Mescle as colunas de Nome e Sobrenome para ter apenas uma coluna definindo os nomes dos colaboradores

13. Mescle os nomes de departamentos e localização. Isso fará que cada combinação departamento-local seja único.
</OL>

## :bar_chart: Meu Relatório  :chart_with_upwards_trend:
Realizei todas as etapas do desafio! Aproveitei e também ajustei um problemas de relacionamento entre tabelas, pois como algumas delas tem o "id", o power bi automaticamente relaciona as tabelas com esse identificador, quando na verdade as chaves são outras colunas.

## :battery: Stack utilizada
![VSCODE](https://img.shields.io/badge/Visual%20Studio%20Code-007ACC.svg?style=for-the-badge&logo=Visual-Studio-Code&logoColor=white)
![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![GIT](https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=Git&logoColor=white)
</p>
