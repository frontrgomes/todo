---Planejamento

Entidades e Relacionamentos

--Usuário

--Usuário x Tarefa
-- Um usuário pode ter várias tarefas

--Usuário x Categoria
-- Um usuário pode ter várias categorias

--Tarefas

--Tarefa x Usuário
-- Uma tarefa sempre vai pertencer a um único usuário

--Tarefa x Categorias
-- Uma tarefa sempre vai pertencer a uma categoria


--Categorias

--Categorias x Tarefa
-- Categoria pode ter uma ou várias tarefas

--Categorias x Usuário
-- Uma categoria sempre vasi pertencer a um usuário

- Detalhamentos das Migrations

Usuário:(user)
----Padrão do Laravel

Tarefa:(tasks)
-id
-titulo
-data
-descrição
-categoria_id
-usuario_id

Categoria(category)
id
nome
cor(hexadecimal)
user_id
