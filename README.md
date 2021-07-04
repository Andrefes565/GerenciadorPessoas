<h2>Digital Innovation: Expert class - Desenvolvendo um sistema de gerenciamento de pessoas em API REST com Spring Boot</h2>

Nesta live coding desenvolvi um sistema para o gerenciamento de pessoas de uma empresa através de uma API REST, criada com o Spring Boot.

<h2>Modificações</h2>
Acrescentei algumas funcionalidaes ao projeto, por exemplo procurar uma pessoa pela FirstName ou pelo lastName
Também acrescentei a uma atributo chamado dataCadastro que é setado automaticamente com a data atual no momento do cadastro


<h2>Durante a sessão, serão desenvolvidos e abordados os seguintes tópicos:</h2>

* Setup inicial de projeto com o Spring Boot Initialzr 
* Criação de modelo de dados para o mapeamento de entidades em bancos de dados
* Desenvolvimento de operações de gerenciamento de usuários (Cadastro, leitura, atualização e remoção de pessoas de um sistema).
* Relação de cada uma das operações acima com o padrão arquitetural REST, e a explicação de cada um dos conceitos REST envolvidos durante o desenvolvimento do projeto.
* Desenvolvimento de testes unitários para validação das funcionalidades

Para executar o projeto no terminal, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080/api/v1/people
```




