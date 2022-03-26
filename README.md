# C# curso da Udemy

Repositório para armazenar tudo que será feito no curso da Udemy.

[C# COMPLETO Programação Orientada a Objetos + Projetos](https://www.udemy.com/course/programacao-orientada-a-objetos-csharp/)
> **Curso mais didático e completo de C# e OO, coleções, UML, ASP.NET, Entity Framework, LINQ, Lambda e muito mais**

## Introdução

### **C# e .NET**

Um pouco sobre a linguagem e o framework.

**C#** é uma linguagem de progração.

**.NET** (lançado inicialmente em 2002) é uma plataforma de desenvolvimento.

O **.NET** possui:

* [BCL](https://docs.microsoft.com/en-us/previous-versions/gg145045(v=vs.110)?redirectedfrom=MSDN) - Base Class Library
* CLR - Common Language Runtime **(Máquina Virtual)**
  * Possui garbage collection.

.NET é uma especificação ([.NET Standard](https://docs.microsoft.com/en-us/dotnet/standard/net-standard?tabs=net-standard-1-0)) e é composto pelas seguintes implementações:

* .NET e .NET Core
* .NET Framework
* Mono
* Xamarin
* Universal Windows Platform
* Unity

![image](https://user-images.githubusercontent.com/11370094/160018932-a8a3890a-1e54-46fe-9851-b73824d25e0f.png)

### **Compilação e Interpretação**

O código de programação escrito por programadores não é compreendido pela máquina, portanto precisa ser transformado em código executável, existem algumas formas a **compilação** e a **interpretação**. 

E também a abordagem híbrida, **"compilação + máquina virtual"**, onde todo o código é pré-compilado e gerado um código intermediário o **"bytecode"** (Common Intermediate Language - CIL) possuindo a vantagem do mesmo código rodar em plataformas diferentes (platform agnostic). 

O ***bytecode*** é executado em uma máquina virtual (Common Language Runtime - CLR) específica para determinado SO. Este processo é chamado compilação ***just-in-time*** (JIT) sendo, mais rápida que a interpretação.

### Estrutura de uma Aplicação .NET

Uma aplicação é composta por **classes**.

Que podem ser agrupadas em ***namespaces*** (agrupamento lógico de classes relacionadas).

![image](https://user-images.githubusercontent.com/11370094/160211236-92444a16-54ed-4ff9-84c8-5f28f83e1462.png)

Também podem ser agrupadas em ***assembly*** (dll ou exe) (agrupamento físico de classes relacionadas, conhecido como build), pode ser feito separando o projeto em subprojetos, gerando executaveis para cada subprojeto.

E por fim existe o agrupamento ***solution*** (aplicação), agrupando assemblies relacionados.

## Estrutura de um programa C#

Como é estruturado e quais os arquivos e extensões de uma aplicação C#.

Estrutura de arquivos:
  * Um projeto C# é uma solução (`.sln`), arquivo no qual é aberto a aplicação em uma IDE.
  * O arquivo `.csproj` contêm as configurações da seu projeto, por exemplo, possui as dependências.
  * Arquivos `.cs` são arquivos da linguagem C#.
  * Por fim, arquivos `obj` e `bin` possui os arquivos compilados, quando é executado a aplicação.

Estrutuda do código:
  * Cláusulas `using`, são referências a outros `namespaces`.
  * Os `namespace` são amplamente usados de duas maneiras, a primeira para organizar suas várias classes e a segunda para ajudar controlar o escopo dos nomes de classe e método em projetos maiores.
  * A **classe** define as propriedades, campos, eventos e métodos de um objeto. Por convenção o nome do arquivo `.cs` tem o mesmo nome da classe.
  * O **método** é um bloco de código que contém uma série de instruções.
  * O `static void Main(string[] args)` é uma declaração padrão para identificar o ponto de entrada da aplicação, ou seja, onde a execução começa.

## Atalhos no Visual Studio Code

**Executar Programa** - CTRL + F5

**Identação Automática** - Shift + Alt + F