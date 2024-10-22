# Trybank

Trybank é uma aplicação desenvolvida em C# durante o curso da Trybe, que simula o controle de contas bancárias e operações financeiras básicas. O sistema permite realizar operações como checar saldo, depositar, sacar, transferir dinheiro, além de serviços de login, logout e cadastro de novas contas.

## Funcionalidades

- **Login** e **logout** de contas bancárias.
- **Cadastro** de novas contas.
- Operações de **checar saldo**, **depósito**, **saque** e **transferência** de dinheiro entre contas.
- Simulação das operações bancárias a partir da execução do arquivo `Program.cs`.

## Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:

- [.NET SDK 6.0 ou superior](https://dotnet.microsoft.com/download)

## Instalação

### 1. Clone o repositório

```bash
git clone https://github.com/arturpeixoto/projeto-trybank.git
```

### 2. Acesse o diretório do projeto

```bash
cd trybank
```

### 3. Restaure as dependências

No diretório raiz do projeto, rode o comando para restaurar os pacotes necessários:

```bash
dotnet restore src/
```

### 4. Execute a aplicação

Para rodar a simulação das operações bancárias, execute o seguinte comando:

```bash
dotnet run --project src/trybank
```

## Como usar

Ao rodar a aplicação, o sistema irá simular uma sequência de operações bancárias como login e operações padrões.

## Tecnologias utilizadas

- C#
- .NET 6

## Contribuição

Contribuições são sempre bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.
