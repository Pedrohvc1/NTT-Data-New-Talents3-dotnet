## **Tipos de valor**

**parte 1. Tipos de variáveis**

- **Tipos de valor **- elas contêm seus dados, as variáveis têm sua própria cópia dos dados e não é possível que as operações afetem outra variável (exceto no caso das variáveis de parâmetro ref ou out)

  - Principais tipos :

    - Numéricas - sbyte, short, int, long, byte ushort, uint, ulong

    - Caracteres Unicode: char

    - Pontos flutuantes : float, doble, decimal

    - Booleano: bool

    - outros : enum, struct e tipos **nullable - ex (int?)**


    

- **Tipos de referência** - variáveis de tipo de referência armazenam referências a seus dados. é possível que duas varáveis façam referência ao mesmo obj e, portanto, que operações em uma variável aferem o obj referenciado pela outra variável.

- tipos Classes: **class, object, string**

- Tipos Arrays: **int[], int[,], etc...**

- **Interface, delegate**

  

**parte 2. Instruções**

Ações de um  programa são expressas usando instruções

{

​	Um bloco permite que várias instruções sejam escritas em    contextos

}

No c# quando nós falamos de instruções, estamos falando de: 

- declaração de variáveis e de constantes

- if - condicionais

- switch - condicionais 

- while - repeticao

- do - repeticao

- for - repeticao

- foreach - repeticao

- Instruções auxiliares assim como:

  <!-- instruções que auxiliam a trabalhar junto com outras instruções -->

  - break -

  - continue 

  - retur

    <!--tratativa de excecions-->

  - throw

  - try .. catch .. finally

    <!--importar referências de pacotes e a namespaces do projeto-->

  - using

parte 3 - **Exemplificando o conteúdo**

os exemplos estao na pasta : **E:\ADS\Digital Inovation One\Primeiros passos com .NET + C#\csharp-examples\02-Instrucoes**



## 																		**Array** 

É uma estrutura de dados que contém um número X de elementos, todos do msm tipo, que são acessados através de índices computados. 

Arrays são tipos de referência e a declaração de uma varável *array* simplesmente reserva espaço para uma referencia de uma instancia de array

ao criar um array é especificado o tamanho da nova instância, que é fixo durante todo o tempo de vida da instancia

O indices dos elementos de um array variam de 0 a comprimento do array - 1

![image-20201122194527406](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122194527406.png)

![image-20201122194734788](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122194734788.png)

![image-20201122195000433](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122195000433.png)