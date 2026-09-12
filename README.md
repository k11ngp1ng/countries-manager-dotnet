# Gerenciador de Países, Estados e Cidades

Aplicação desktop em C# para cadastro e consulta de países, estados e cidades, com organização em entidades, controladores e acesso a dados.

## Objetivo

Praticar conceitos de desenvolvimento desktop orientado a objetos e persistência de dados em um domínio com relacionamentos hierárquicos.

## Funcionalidades

- Cadastro de países, estados e cidades
- Consultas das entidades cadastradas
- Navegação por telas do Windows Forms
- Operações de acesso a dados organizadas por DAO
- Separação entre entidades, controladores e formulários

## Tecnologias

- C#
- Windows Forms
- .NET
- SQL

## Arquitetura

| Componente | Responsabilidade |
| --- | --- |
| `Paises.cs`, `Estados.cs`, `Cidades.cs` | Entidades do domínio |
| `CtrlPaises.cs`, `CtrlEstados.cs`, `CtrlCidades.cs` | Regras de controle e orquestração |
| `DaoPaises.cs`, `DaoEstados.cs`, `DaoCidades.cs` | Acesso a dados |
| `Frm*.cs` | Interfaces de cadastro e consulta |
| `SQLQuery*.sql` | Scripts SQL do projeto |

## Como executar

1. Abra `ProjetoElp4Paises.sln` no Visual Studio.

2. Configure a conexão com o banco de dados conforme o arquivo de configuração e os scripts SQL do repositório.

3. Compile e execute o projeto pela IDE.

## Aprendizados

- Modelagem de relacionamentos entre entidades.
- Organização em camadas para aplicações desktop.
- Criação de interfaces de cadastro e consulta com Windows Forms.
- Integração de uma aplicação C# com banco de dados relacional.

## Próximos passos

- Centralizar a configuração de conexão em variáveis de ambiente.
- Adicionar validações e tratamento de erros mais detalhados.
- Criar testes para regras de negócio e acesso a dados.
