1) Os paradigmas de programação

O que são os paradigmas de programação:![image-20201215230946942](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201215230946942.png)

paradigma lógico - que cada programador tem sua lógica, seu caminho, mas o importante é chega no msm fim.

![image-20201216130258362](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216130258362.png)

cada paradigma tbm nos leva a situações diferentes na programação, a programação estruturada é diferente da prog orientada a obj.

**Programação estruturada **![image-20201216131957271](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216131957271.png)

- **sequencias **: são comando a serem executados de cima para baixo, linha a linha, do programa, de forma sequencial.
- **seleções **: sequencias que só devem ser executadas se uma condição for satisfeita (exemplo: if-else, switch e comandos parecidos).
- **repetições ** - sequências que devem ser executadas repetidamente até uma condição for satisfeita (for, while, do-while, etc).



**Programação Orientada a objetos **![image-20201216132427553](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216132427553.png)

Pilares da POO![image-20201216133130798](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216133130798.png)

**Orientação a obj em .NET **![image-20201216133305095](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216133305095.png)



2)O que são classes, objetos e visibilidade

Classes - ela é como se fosse um molde para o obj, a planta do obj, um modelo.![image-20201216133528802](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216133528802.png)

UML - é um linguagem universal de modelagem, ela define alguns diagramas como esse, onde nós podemos modelar uma classe.![image-20201216133817880](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216133817880.png)

![image-20201216134647632](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216134647632.png)

Objetos![image-20201216134708352](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216134708352.png)

![image-20201216134820103](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216134820103.png)

Visibilidade![image-20201216135130672](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216135130672.png)

Comportamento dos modificadores:

- public - sem limitação de acesso
- protected internal - acesso limitado à própria classe, as classes derivadas e ao próprio assembly(montador)
- protected - acesso limitado a própria classe e as classes derivadas
- internal - acesso limitado ao próprio assembly
- private - acesso limitado a própria classe.

Essa situação de visibilidade é chamado de ENCAPSULAMENTO![image-20201216135606127](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216135606127.png)

![image-20201216135837244](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216135837244.png)



3) Tipos por valor, referência e ponteiro

**Tipos por valor: **

- Todos os tipos de dados numéricos
- Não precisam ser inicializados com  o operador new
- A variável armazena o valor diretamente
- A atribuição de uma variável a outra copia o conteúdo, criando efetivamente outra cópia da variável (basicamente quando é criada uma variável com o mesmo nome, ela cria uma cópia)
- Não podem conter o valor null
- Exemplos de variáveis desse tipo são: **Integers, doubles, floats e char **

Inteiros(Integers)![image-20201216140913186](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216140913186.png)

Double e Float![image-20201216141212983](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216141212983.png)

char(caracteres)![image-20201216141329569](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216141329569.png)



**Tipos por referência: ** 

Armazena uma referencia a seus dados. Os tipos de referencia incluem o seguinte:

- Duas variáveis poderem conter a referencia a um mesmo objeto
- Opereções em uma afetarem a outra
- Todas as matrizes, mesmo que seus elementos sejam de tipos de valor
- Exemplos de tipos por referencia: **strings, classes e arrays **

String![image-20201216141918420](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216141918420.png)![image-20201216141947134](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216141947134.png)

Classes![image-20201216142029317](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216142029317.png)

array![image-20201216142118580](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216142118580.png)

Ponteiro![image-20201216171042351](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171042351.png)



4)Metodos e tipos de métodos

Metodos![image-20201216171231140](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171231140.png)

![image-20201216171405562](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171405562.png)

Tipos de métodos:

- Get - com o get podemos inserir, pesquisar o produto sem altera-lo

  ![image-20201216171514951](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171514951.png)

  ![image-20201216171728936](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171728936.png)

- Set - diferente do get ele altera o produto.

  ![image-20201216171757243](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171757243.png)

  ![image-20201216171859425](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216171859425.png)

- construct

  ![image-20201216172016008](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216172016008.png)

  ![image-20201216172204087](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216172204087.png)



5) Conhecendo sobre propriedades e eventos em orientação a objetos

**Propriedades **![image-20201216172441263](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216172441263.png)

Geralmente, para cada método existe uma variável dentro da classe que armazena o valor da propriedade.

**Eventos **![image-20201216174556778](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216174556778.png)

- Delegate![image-20201216174825152](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20201216174825152.png)

