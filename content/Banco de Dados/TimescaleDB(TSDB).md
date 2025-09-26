Banco de dados de código aberto desenvolvido para tornar o SQL escalável para dados de séries temporais, implementado no PostgreSQL.
Faz com que o banco de dados trate tabelas especificadas como dados em séries temporais 

![[Pasted image 20250913130458.png]]

Hypertable é a camada de abstração (é uma interface de software que oculta a complexidade interna do PostgreSQL e permite que aplicações se comuniquem com o banco de dados sem precisar conhecer seus detalhes de implementação específicos) que particiona tabelas, primeiramente por tempo com a finalidade de aumentar a performance tanto da ingestão de dados quanto a querying.
A Hypertable é automaticamente dividida em chunks.

