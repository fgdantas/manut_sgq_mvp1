# Telas do MVP 1

## Visão geral
O MVP 1 do sistema foi definido para atender o fluxo mínimo de controle de manutenção da empresa, com foco em cadastro de ativos, planejamento de preventivas, registro de corretivas e rastreabilidade por histórico.

As telas foram organizadas para cobrir as operações essenciais do sistema.

---

## 1. Dashboard

### Objetivo
Apresentar uma visão geral rápida da situação das manutenções.

### Informações exibidas
- quantidade de preventivas vencidas
- quantidade de manutenções programadas para hoje
- quantidade de equipamentos em manutenção
- quantidade de ordens abertas

### Finalidade
Permitir acompanhamento inicial da situação operacional do sistema.

---

## 2. Lista de Máquinas e Equipamentos

### Objetivo
Permitir consultar os ativos cadastrados no sistema.

### Funcionalidades
- busca por código, nome ou setor
- exibição em tabela
- acesso ao cadastro de novo equipamento

### Informações exibidas
- código
- nome
- tipo
- setor
- status

### Finalidade
Centralizar a visualização dos ativos controlados no sistema.

---

## 3. Cadastro de Novo Equipamento

### Objetivo
Permitir o cadastro de máquinas e equipamentos no sistema.

### Campos principais
- código
- nome
- tipo
- setor
- fabricante
- modelo
- status

### Finalidade
Garantir a criação da base de ativos necessária para o funcionamento do sistema.

---

## 4. Lista de Preventivas

### Objetivo
Permitir consultar as manutenções preventivas cadastradas.

### Funcionalidades
- visualização em tabela
- filtro por equipamento, responsável ou status
- acesso ao cadastro de nova preventiva

### Informações exibidas
- equipamento
- atividade
- frequência
- próxima execução
- responsável
- status

### Finalidade
Acompanhar as preventivas planejadas e identificar manutenções vencidas ou próximas.

---

## 5. Cadastro de Nova Preventiva

### Objetivo
Permitir o cadastro de uma nova manutenção preventiva.

### Campos principais
- equipamento
- descrição da atividade
- frequência
- responsável
- próxima execução
- observações

### Finalidade
Permitir o planejamento básico das manutenções periódicas.

---

## 6. Lista de Corretivas / Ordens de Serviço

### Objetivo
Permitir consultar as manutenções corretivas registradas.

### Funcionalidades
- visualização em tabela
- filtro por equipamento, data, responsável ou status
- acesso ao cadastro de nova corretiva

### Informações exibidas
- número da OS
- equipamento
- data
- problema
- responsável
- status

### Finalidade
Acompanhar as ocorrências corretivas e o andamento das ordens de serviço.

---

## 7. Cadastro de Nova Corretiva / Ordem de Serviço

### Objetivo
Permitir registrar uma nova manutenção corretiva.

### Campos principais
- equipamento
- data
- problema
- ação realizada
- responsável
- tempo parado
- peças trocadas
- status

### Finalidade
Registrar falhas e intervenções realizadas nos equipamentos.

---

## 8. Histórico

### Objetivo
Permitir consultar o histórico de manutenções por equipamento.

### Funcionalidades
- filtro por equipamento
- filtro por período
- filtro por tipo de manutenção

### Informações exibidas
- data
- equipamento
- tipo de manutenção
- descrição
- responsável
- status

### Finalidade
Garantir rastreabilidade das intervenções e apoio ao controle operacional e ao SGQ.
