# 🔧 Projeto de Banco de Dados - Oficina Mecânica

## 📌 Sobre

Projeto de modelagem de banco de dados para um sistema de controle e gerenciamento de ordens de serviço em uma oficina mecânica, desenvolvido para praticar conceitos de modelagem Entidade-Relacionamento (ER) e refinamento de regras de negócio.

## 🖼️ Diagrama

![Diagrama Oficina](https://github.com/eliorocha21/OficinaMecanica-db/blob/main/Oficina%20Mecanica.png)

## 🎯 Regras de Negócio

* Um cliente pode possuir vários veículos;
* Cada veículo pode gerar várias ordens de serviço (OS);
* Uma ordem de serviço é atribuída a uma equipe de mecânicos;
* Uma equipe pode ter vários mecânicos, e um mecânico pode participar de várias equipes (N:M);
* Cada OS possui data de emissão, data de conclusão, valor total e status;
* Uma OS pode conter vários serviços e várias peças;
* O valor da OS é calculado a partir da mão de obra e das peças utilizadas.

## 🔧 Refinamentos Aplicados

* Entidade associativa **Equipe_Mecanico** para representar equipes de trabalho;
* Entidade associativa **Itens_OS** para detalhar serviços e peças vinculados a cada OS;
* Relacionamentos entre **Cliente, Veículo, OS, Equipe, Mecânicos, Serviços e Peças**;
* Controle de status da OS (Aberta, Em execução, Concluída, Cancelada).

## 🛠️ Ferramentas

* MySQL Workbench  
* MySQL  
* Git & GitHub  

## 🚀 Objetivo

Aplicar conceitos de modelagem de dados em um cenário real de oficina mecânica, consolidando conhecimentos de banco de dados e estruturação de regras de negócio.
