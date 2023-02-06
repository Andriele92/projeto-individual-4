# projeto-individual 4 - BANCO DE DADOS 
Para apoiar nesse sistema recebemos a tarefa de realizar essa modelagem
e responder algumas perguntas com nosso modelo:
⇨ Existem outras entidades além dessas três?
Sim, entidades como funcionarios, outros curso do estabeleciomento e etc;
⇨ Quais são os principais campos e tipos?
Aluno
nome varchar  (50),
rg int primary key,
idade int,
cpf varchar (15),
matricula varchar (4));

Turma
id int primary key,
nome_do_curso varchar (50),
disciplinas varchar (50),
horario float,
modulos int);

Curso
id int primary key,
nome varchar (50),
sala int,
modulos int,
valor int);

⇨ Como essas entidades estão relacionadas?
Sim, porque a entidades aluno, se relaciona com a turma que possui outros alunos e professores que são entidades. E também com o curso.
(1,1)
(0,n)
(1,n)


