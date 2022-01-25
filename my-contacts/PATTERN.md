# Repository Pattern

- **Data Source**: Fonte de Dados (Array, SQL, NoSQL, .json,API)

- **Repository Pattern**: Layar(camada) de abstração do acesso ao **Data Source**

```
Controller <--> Data Source
Controller <--> Repository.create <--> Data Source
```

## O que e o Repository Pattern ?

- Sua utilização contribui no isolamento da camada de acesso a dados (DAL) com a camada de negócio, mais conhecida como camada de domínio.

- O Repository Pattern **permite um encapsulamento da lógica de acesso a dados**, impulsionando o uso da injeção de dependencia (DI) e proporcionando uma visão mais orientada a objetos das interações com a DAL.

# Singleton Pattern

- **Singleton especifica que apenas uma instância da classe pode existir**, e esta será utilizada por toda a aplicação. Dessa forma temos apenas um ponto de acesso central a esta instância da classe.

## Quando utilizar o Singleton Pattern ?

- Quando você precisar controlar a concorrência de acesso a recursos compartilhados;

- Quando uma classe for utilizada com frequência por várias partes distintas do sistema, e essa classe não gerencia nenhum estado da aplicação;
