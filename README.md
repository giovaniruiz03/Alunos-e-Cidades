# Alunos-e-Cidades
Tarefa Banco de dados - Alunos e Cidades (INNER JOIN E ALIASES)

# Tópico 1 
select * from tb_alunos inner join tb_cidades on tb_cidades.id = tb_alunos.cidade_id;

![image](https://github.com/giovaniruiz03/Alunos-e-Cidades/assets/145368122/520f657c-7fd4-4e68-b60a-298919f5f3d3)

# Tópico 2 
select * from tb_alunos left join tb_cidades on tb_cidades.id = tb_alunos.cidade_id;

![image](https://github.com/giovaniruiz03/Alunos-e-Cidades/assets/145368122/9622b44d-26a4-4403-afa6-ab3914483c2c)

# Tópico 3 
select * from tb_alunos right join tb_cidades on tb_cidades.id = tb_alunos.cidade_id;

![image](https://github.com/giovaniruiz03/Alunos-e-Cidades/assets/145368122/68c49ef6-4011-4e9b-bd75-8b35f17e7e70)

# Tópico 4 
select nome as "Nome" , data_nasc as "Data de Nascimento" from tb_alunos;

![image](https://github.com/giovaniruiz03/Alunos-e-Cidades/assets/145368122/46d822e7-5217-40be-a4c7-0da1c9ebd9eb)

# Tópico 5 
select a.id as "RA",
       a.nome as "Nome",
       a.data_nasc as "Data de Nascimento",
       c.nome as "Cidade" 
       
   from tb_alunos  a left join 
        tb_cidades c on a.cidade_id = c.id
   where c.nome like "Hi%" and a.data_nasc > '2001-08-15' order by a.nome;     

   ![image](https://github.com/giovaniruiz03/Alunos-e-Cidades/assets/145368122/e43ad902-fe9d-4f27-b20e-95b14e4d6e66)

   ## Aluno: Giovani Boccardo Ruiz - RA: 223102 - giruiz2003@gmail.com 




