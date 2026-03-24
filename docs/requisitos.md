# Requisitos do MVP 1

## Requisitos funcionais

### RF01 - Cadastro de máquinas e equipamentos
O sistema deve permitir cadastrar máquinas e equipamentos com os seguintes campos:
- código
- nome
- tipo
- setor
- status

### RF02 - Cadastro de manutenção preventiva
O sistema deve permitir cadastrar manutenções preventivas com:
- equipamento relacionado
- descrição da atividade
- frequência
- responsável
- próxima execução

### RF03 - Lista de preventivas
O sistema deve exibir uma lista com:
- equipamento
- atividade
- frequência
- próxima execução
- responsável
- status

### RF04 - Registro de manutenção corretiva
O sistema deve permitir registrar manutenções corretivas com:
- equipamento
- data
- problema
- ação realizada
- responsável
- tempo parado

### RF05 - Histórico de manutenções
O sistema deve permitir consultar o histórico das manutenções por equipamento.

### RF06 - Dashboard inicial
O sistema deve exibir um painel simples com:
- preventivas vencidas
- preventivas programadas
- equipamentos em manutenção
- ordens abertas
