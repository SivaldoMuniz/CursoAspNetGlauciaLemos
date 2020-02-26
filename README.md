# CursoAspNetGlauciaLemos  - 21/02/2020
Repositório responsável pelos códigos desenvolvidos durante o  Live Coding no **[Twitch]()** e **[Youtube]()** a qual estaremos desenvolvendo alguns projetos em .Net Core 3.x

## Rercusos Utilizados

* **[Download .NET Core 3.x](https://aka.ms/AA69q93)**
* **[Visual Studio Code]()**
* **[Git hub como ferramenta de visionamento]()**

## Recursos Adicionais & Links Importantes

Durante a live, comento de alguns links e recursos improtantes para aprofundar seus conhecimentos sobre .NET Core. São eles:

##Executando a Apicação Localmente 💥

Para executar localmente a aplicação você precisa entrar na  pasta 'src -> filmeslivecoding' e executar o seguinte comando: 

'''bash
dotnet run
¨¨¨¨
-FilmeId
-Data de Lançamento
-Gênero
-Preço

Para qye, possamnos executar o 'Entity Framework' no projet, se faz necesssário executar os seguintes comadndos dentro da apsta 'src -> filmeslivecoding'
```bash
> dotnet tool install --global dotnet -ef
> dotnet add  package Microsft.VisualStudio.Web.CodeGeneration.Design
> dotnet add package Microsoft.EntityFrameworkCore.Design
> dotnet add package Microsoft.EntityFrameworkCore.Sqlite
> dotnet add package Microsoft.EntityFrameworkCore.SqlServer
> dotnet restore
> dotnet ef migrations add InitialCreate
> dotnet ef database update

..|