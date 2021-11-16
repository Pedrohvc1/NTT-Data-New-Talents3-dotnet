## **O que são Classes e Objetos em C#**

1. Classes

   são os tipos mais fundamentais do C#, ela é uma estrutura de dados que combina estado (campos, propriedades) e ações (métodos q o obg vai executar).

2. Objetos

   São instâncias de uma classe, eles suportam herança e polimorfismo, mecanismos pelos quais as classes derivadas podem estender e especializar as classes base



no exemplo abaixo, existe uma classe Ponto, suas variaveis int x, y e um CONSTRUTOR public Ponto(int x, int y)

![image-20201122201236058](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122201236058.png)

Instancias de classes (objetos) são criadas usando o operador new, que aloca memoria para uma nova instancia, chamada um construtor para inicializar a instancia e retorna uma referencia a instancia.

Ponto p1 = new Ponto (0, 0)

Ponto p2 = new Ponto (10, 20)

A memória ocupada por um objeto é recuperada automaticamente quando o objeto não está mais acessível. Não é necessário nem possível desalocar explicitamente objetos em C# - isso é um papel do Garber collector



![image-20201122202035025](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122202035025.png)

![image-20201122202126018](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122202126018.png)

public - pode ser acessado de qualquer classe

protected - só as classes que erdam da classe base tem acesso ao obj protected

internal - dessa forma ele so é acessado dentro do assembly que ele é instanciado

private - indica que ele só é acessado dentro da classe que ele está contido

![image-20201122202511485](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122202511485.png)

![image-20201122203616917](C:\Users\PEDRO CAVALCANTI\AppData\Roaming\Typora\typora-user-images\image-20201122203616917.png)

obs - Quando vamos dar o nome a um método, é importante que declaramos ele com verbo, e as propriedades como substantivo

