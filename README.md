# Calculadora de Operações Matemáticas - Projeto de Testes Unitários

Este projeto tem como objetivo implementar uma calculadora simples que realiza operações matemáticas de soma e multiplicação, além de testar essas funcionalidades utilizando três frameworks de testes diferentes: **MSTest**, **xUnit** e **NUnit**.

## Funcionalidades

- **Somar**: Recebe dois números e retorna a soma.
- **Multiplicar**: Recebe dois números e retorna o produto.

## Estrutura do Projeto

O projeto está organizado da seguinte forma:

- `teste_exemplo`: Implementação inicial com métodos de soma e multiplicação e testes com **xUnit**.
- `teste_calculadora_mstest`: Implementação das operações e testes utilizando o framework **MSTest**.
- `teste_calculadora_xunit`: Implementação das operações e testes utilizando o framework **xUnit**.

### Arquivos Principais:

#### Operações
- `Operacoes.cs`: Contém a lógica de soma e multiplicação para ser testada.

#### Testes
- **xUnit**: 
  - `UnitTest1.cs`: Testes unitários das operações utilizando o framework xUnit.
  
- **MSTest**: 
  - `UnitTest1.cs`: Testes unitários das operações utilizando o framework MSTest.

- **NUnit**: (Adicionar caso haja implementação futura)

## Pré-requisitos

Antes de começar, você vai precisar ter as seguintes ferramentas instaladas:

- [.NET SDK](https://dotnet.microsoft.com/download)
- [Visual Studio](https://visualstudio.microsoft.com/) ou [Visual Studio Code](https://code.visualstudio.com/)

## Como executar o projeto

1. **Clone o repositório**:
   ```bash
   git clone https://github.com/usuario/repositorio-calculadora.git
   ```

2. **Navegue até o diretório do projeto**:
   ```bash
   cd repositorio-calculadora
   ```

3. **Restaure as dependências e compile o projeto**:
   ```bash
   dotnet restore
   dotnet build
   ```

4. **Execute os testes**:
   Para executar os testes com **MSTest** ou **xUnit**, navegue até a pasta do respectivo framework e rode o comando:

   - **MSTest**:
     ```bash
     dotnet test teste_calculadora_mstest
     ```

   - **xUnit**:
     ```bash
     dotnet test teste_calculadora_xunit
     ```

## Tecnologias Utilizadas

- **C#**
- **.NET Core**
- **MSTest**
- **xUnit**

## Autor

- **Sérgio Fonte** - Desenvolvedor e criador dos testes (Para SENAI)