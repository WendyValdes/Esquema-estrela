Projeto de Modelagem Dimensional – Análise de Professores

- Descrição do Projeto

Este projeto consiste na criação de um modelo dimensional no formato Star Schema, com foco na análise de dados relacionados aos professores, seus cursos, disciplinas e departamentos.
O modelo foi desenvolvido com base em um diagrama relacional previamente fornecido, aplicando conceitos de Data Warehouse e Business Intelligence.


- Objetivo

Construir um modelo dimensional que permita análises eficientes sobre:

Professores

Disciplinas ministradas

Cursos ofertados

Departamentos

Evolução temporal das ofertas

O foco principal é o Professor como objeto de análise.


- Conceitos Aplicados

Modelagem Dimensional

Star Schema

Tabela Fato e Tabelas Dimensão

Data Warehouse

Granularidade

Chaves Primárias e Estrangeiras

Dimensão Tempo


- Estrutura do Modelo

O modelo é composto por:

Tabela Fato: FATO_PROFESSOR_DISCIPLINA

Tabelas Dimensão: DIM_professor, Dim_curso, Dim_departamento, Dim_disciplina, Dim_tempo


- Tecnologias Utilizadas

MySQL

MySQL Workbench

SQL

Modelagem Dimensional

EER Diagram

 
- Possíveis Análises

Quantidade de disciplinas por professor

Carga horária por departamento

Professores mais ativos

Disciplinas mais ofertadas

Análise temporal de ofertas


- Aprendizados

Este projeto permitiu aplicar na prática:

Criação de Star Schema

Definição de granularidade

Construção de tabelas fato e dimensão

Modelagem para suporte à análise de dados
