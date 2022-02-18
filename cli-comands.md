# Command Line Interface .NET (CLI)
Orientações e comandos para serem utilizados via CLI para desenvolvimento e execução de aplicações .NET

### Documentação dos comandos:
> dotnet -h 

### Criar projeto:
- Console:
  > dotnet new console
- Classlib:
  > dotnet new classlib
- Web:
  > dotnet new web
- MVC:
  > dotnet new mvc
- WebAPI:
  > dotnet new webapi
- MSTest:
  > dotnet new mstest
- API:
  > dotnet new webapi -n _nome_ -o _caminho_

### Verificar projeto:
> dotnet build _caminho_

### Executar projeto:
> dotnet run -p _caminho_

### Processo de Execução:
- dotnet restore:
  > Baixar todas as dependencias que essa aplicação precisa para executar e realiza instalação deles
- dotnet build:
  > Realiza a compilação do projeto
- dotnet clean:
  > Limpa os itens em cache
- dotnet run:
  > Executa a aplicação
  