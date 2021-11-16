2. **Conhecendo a CLI do .NET**

**dotnet --help**![image-20201120184735134](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201120184735134.png)

![image-20201120185220218](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201120185220218.png)

3. **Criando uma aplicação console**

   - dotnet new --help
   - dotnet new console -h![image-20201120190043037](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201120190043037.png)
   - dotnet new console -n **nome arquivo**
   - para abrir o arquivo criado comando: **code .**

   **dotnet restore -** restaura os pacotes

   **dotnet build** - para compilar o código fonte e gerar as DLL's?

**--> sobre o .csproj**

- Project Sdk="Microsoft.NET.Sdk"> *informando que é um projeto .net*

   <PropertyGroup>

    <OutputType>Exe</OutputType> *fala que o output vai gerar um arq executavel*

    <TargetFramework>net5.0</TargetFramework> *qual o framework que uso*

   </PropertyGroup>

  </Project>

