# Modelagem do Banco de Dados

## usuarios
- id (PK)
- nome
- email
- senha
- tipo (admin | cliente)

## servicos
- id (PK)
- nome
- duracao_minutos
- preco

## agendamentos
- id (PK)
- data
- hora
- usuario_id (FK)
- servico_id (FK)
- status
## Regras de Negócio
- Um horário não pode ter dois agendamentos ativos
- Apenas administradores podem cadastrar serviços
- Um agendamento pertence a um cliente
