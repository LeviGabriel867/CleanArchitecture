**Descrição**
O projeto Clean Architecture é uma aplicação de exemplo desenvolvida para demonstrar a aplicação dos princípios de Clean Architecture, que visa criar um código modular, escalável e de fácil manutenção. Utiliza C# e ASP.NET Core para o desenvolvimento do back-end, e Entity Framework para a interação com o banco de dados. A arquitetura é projetada para promover a separação clara de responsabilidades, facilitando a manutenção e expansão do sistema.

**Tecnologias Utilizadas**
Linguagem de Programação:

- C#: Linguagem principal utilizada para o desenvolvimento da aplicação.

**Frameworks e Bibliotecas:**

- ASP.NET Core: Framework para construção de APIs e aplicações web.
- Entity Framework: ORM (Object-Relational Mapper) para acesso e manipulação do banco de dados.

**Banco de Dados:**
- SQL Server: Banco de dados relacional utilizado para persistência de dados.

**Outras Ferramentas:**
- AutoMapper: Para mapeamento de objetos e simplificação da conversão entre DTOs e entidades.
- MediatR: Biblioteca para implementação de padrões CQRS e Mediator, facilitando a comunicação entre componentes.

**Funcionalidades**
- API RESTful: Implementação de uma API RESTful para manipulação de entidades, permitindo operações CRUD (Create, Read, Update, Delete).
- Arquitetura Modular: Segue os princípios de Clean Architecture, organizando o código em camadas distintas (Presentation, Application, Domain, Infrastructure).
- DTOs e Mapeamento: Utiliza DTOs (Data Transfer Objects) para comunicação entre camadas e AutoMapper para simplificação do mapeamento.
