## **Conhecendo o C#**

**o que é o C# ? ** 

- é uma ling que começou a ser criada na decada de 90 surgio oficialmente em 2000 e vem sendo evoluida ao longo dos anos junto com o .NET
- quando falamos de .NET, c# podemos dizer que é a ling oficial
- segundo a documentação C# é uma linguagem elegante , orientada a obj e fortemente tipada
- A sintaxe do C# é similar a do C, C++ ou JAVA
- Ela suporta os conceitos da orientação a obj - encapsulamento , herança e polimorfismo (OO)
- os programas c# sao executados no .NET, que inclui:
  - CLR 
  - Conjunto unificado de biblioteca de classes
- Atualmente o compilador do C# é o **Roslyn**

**Como funciona?**

O cod-fonte escrito em c# é compilado em uma linguagem intermediária (IL)

o cod e os recurso de IL sao armazenados no disco em um arquivo executável chamado assembly, geralmente com uma extensao **.exe** ou **.dll**

Quando o programa C# é executado, o assembly é carregado no CLR, em seguida o CLR executará a compilação **just in time** (JIT) para converter o cod IL em instruções de maquinas nativas.

O CLR tbm fornece outros serviços:

- **Garbage Collectot** - colhetor de lixo(ele verifica obj da memoria q n estao sendo mais utilizados e desaloca esses obj da memoria, para liberar espaço)
- **Exception Handler** -  serve para receber e controlar as excessos de erro no cod.
- **Resources Manager** - gerenciador de recursos

![image-20201121200601673](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201121200601673.png)

Alem dos serviços de tempo de exeção, o .NET tbm inclui uma extensa biblioteca com milhares de classes que fornecem uma ampla variedade de funcionalidades úteis, desde entrada e saída de arquivos, manipulação de cadeias de caracteres, análise XML, etc

## **Estrutura de Programa**

Os principais conceitos organizacionais em C# são:

- programas
- namespaces
- tipos
- membros
- assemblies (dlls)

Programas C# consistem em um ou mais arquivos com extensão .cs, eles declaram tipos, que contêm membros e podem ser organizados em **namespaces**.

Classes e interfaces são exemplos de **tipos**

Campos, métodos, propriedades e eventos são exemplos de **membros**.

Quando os programas c# são compilados, eles sao fisicamente empacotados em assemblies, os assemblies geralmente têm a extensão de arquivos .exe ou .dll, dependendo se são aplicações ou bibliotecas.

about.me/gabrielfaraday