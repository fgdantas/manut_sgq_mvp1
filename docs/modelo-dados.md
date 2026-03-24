# Modelo de Dados - MVP 1

## Entidade: Equipamento
Campos:
- id
- codigo
- nome
- tipo
- setor
- status

## Entidade: Preventiva
Campos:
- id
- equipamento_id
- descricao
- frequencia
- responsavel
- proxima_execucao
- status

## Entidade: Corretiva
Campos:
- id
- equipamento_id
- data
- problema
- acao_realizada
- responsavel
- tempo_parado

## Entidade: Histórico
O histórico pode ser formado a partir dos registros de preventivas e corretivas vinculados ao equipamento.
