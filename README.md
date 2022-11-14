# exercicios-bd-tarde
Exercícios para o módulo de Banco de Dados

01 - Crie uma base de dados com o nome curso_programacao com as tabelas a seguir:

Obs. levar em consideração para o campo sexo 0 = masc, 1 = fem

-tb_alunos (id, fk_cidade, nome, endereço, numero_casa, nascimento, telefone, sexo)

-tb_cidades (id, nome, estado, abv_estado)


1.1 - adicionar as informacções na tb_alunos

('4', 'maria', 'marte', '37', '1988-04-01', '99999-9991', '1'),

('1', 'calos', 'aleixo', '244', '2004-02-02', '99999-9992', '0'),

('1', 'cleuza', 'abraao glasser', '1567', '1969-04-29', '99999-9993', '1'),

('2', 'beatriz', 'vicente machado', '03', '1995-08-02', '99999-9994', '1'),

('1', 'marlon', 'balduino taques', '29', '2000-12-02', '99999-9995', '0');


1.2 - adicionar as informações na tb_cidades

('ponta grossa', 'parana', 'pr'),

('curitiba', 'parana', 'pr'),

('camboriu', 'santa catarina', 'sc'),

('caixias do sul', 'rio grande do sul', 'rs');

Obs. se atentar para os atributos de integridade referencial.


02- Abram um arquivo de texto e insiram os registros encontrados, identifique a questão e coloque a resposta abaixo.
Para subir no reposiório.

A- Selecione todos os registros da tabela tb_alunos.

B- Selecione todos os registros da tabela tb_cidades.

C- Selecione da tabela tb_alunos os alunos residentes em ponta grossa, apresentando apenas o sua primary key e nome.

D- Selecione todos os alunos com todas as suas informações.

E- Selecione todos os alunos do sexo feminino, apresentando os seus nomes e data de nascimento.

F- Selecione o(s) aluno(s) residente no Rio Grande do Sul, informse sua primary key, nome e sexo.


