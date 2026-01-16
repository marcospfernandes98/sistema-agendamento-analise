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
