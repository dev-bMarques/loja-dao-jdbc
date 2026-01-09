🛒 Loja DAO com JDBC
Este projeto foi desenvolvido com o objetivo de estudar e praticar o acesso a banco de dados em Java, utilizando JDBC e aplicando o padrão de projeto DAO (Data Access Object).
Ele simula uma estrutura básica de uma loja, focando na organização do código, separação de responsabilidades e boas práticas em aplicações backend.

O principal objetivo deste projeto é consolidar conceitos fundamentais do desenvolvimento backend em Java, especialmente:
-> Conexão com banco de dados relacional;
-> Execução de comandos SQL via Java;
-> Organização do código utilizando padrões de projeto;
-> Estruturação de um projeto Java voltado para persistência de dados;

Este repositório faz parte do meu processo de aprendizado e evolução na área de desenvolvimento de software.

O que eu estudei e pratiquei neste projeto

🔹 Java e Programação Orientada a Objetos;
Criação de classes e métodos;
Encapsulamento;
Organização de pacotes;
Separação entre camadas da aplicação;

🔹 JDBC (Java Database Connectivity)
Configuração de conexão com banco de dados;
Uso de Connection, PreparedStatement e ResultSet;
Execução de comandos SQL diretamente pelo Java;
Tratamento de exceções relacionadas a banco de dados;
Fechamento correto de recursos para evitar vazamentos;

🔹 Padrão de Projeto DAO (Data Access Object)
Criação de uma camada exclusiva para acesso a dados;
Isolamento da lógica de persistência da lógica de negócio;
Facilidade de manutenção e leitura do código;
Base sólida para evolução futura com frameworks ORM (como JPA/Hibernate);

🔹 CRUD com Banco de Dados
Create – inserção de dados;
Read – busca de registros;
Update – atualização de dados;
Delete – remoção de registros;


🔹 Boas práticas
Uso de arquivo db.properties para externalizar configurações;
Código mais limpo e organizado;
Estrutura pensada para escalabilidade e manutenção;
Versionamento com Git e GitHub;


🗂️ Estrutura do projeto
loja-dao-jdbc/
├── src/                # Código-fonte Java
├── db.properties       # Configurações de conexão com o banco
├── .classpath
├── .project
├── .settings/
└── .gitignore

🛠️ Tecnologias utilizadas
Java
JDBC
SQL
Git & GitHub
IDE: Eclipse

🚀 Próximos passos
Criar um README ainda mais detalhado com exemplos de uso;
Melhorar tratamento de exceções;
Implementar testes;
Evoluir o projeto para uso de JPA/Hibernate;
Criar uma camada de serviço (Service Layer);


📌 Fique à vontade para explorar o projeto e acompanhar minha evolução 🚀
 
