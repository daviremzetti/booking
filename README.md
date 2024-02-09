# booking
 RestApi para cadastro de reservas em mesas de estabelecimentos.
 Regra de negócios:
 - Uma mesa, de um mesmo estabelecimento, numa mesma data, só pode ser reservada uma única vez.
 - Caso algum cliente queira reservar uma mesa de um determinado estabelecimento, em uma determinada data, e a mesma estiver ocupada, a reserva não é concluída.
 - Só é possível reservar mesas para datas dentro do perído dos próximos 30 dias.
 - Todos os campos para cadastro são obrigatórios
 - CPF e e-mail devem ser válidos.

Tecnologias envolvidas:
- JAVA
- MAVEN
- Spring Web
- Spring data
- Spring validation
- Lombok
- Banco de dados MySQL
