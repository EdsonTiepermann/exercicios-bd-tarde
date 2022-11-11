# exercicios-bd-tarde
Exercícios para o módulo de Banco de Dados

01 - Crie uma base de dados curso_programacao com as tabelas a seguir:

-tb_alunos (id, fk_cidade, nome, endereço, numero_casa, nascimento, telefone)

-tb_cidades (id, nome, estado, abv_estado)

-tb_estados (id, nome, abv_nome)


1.1 - adicionar as informacoes na tb_alunos

('', 'maria', 'marte', '37', '1988-04-01', '99999-9991'),
('', 'calos', 'aleixo', '244', '2004-02-02', '99999-9992'),
('', 'cleuza', 'abraao glasser', '1567', '1969-04-29', '99999-9993'),
('', 'beatriz', 'vicente machado', '03', '1995-08-02', '99999-9994'),
('', 'marlon', 'balduino taques', '29', '2000-12-02', '99999-9995');

1.2 - adicionar as informacoes na tb_cidades

('', 'ponta grossa', 'parana', 'pr'),
('', 'curitiba', 'parana', 'pr'),
('', 'camboriu', 'santa catarina', 'sc'),
('', 'caixias do sul', 'rio grande do sul', 'rs');


02 - Adicione os id da tb_cidades, nos fk da tb_alunos.
