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