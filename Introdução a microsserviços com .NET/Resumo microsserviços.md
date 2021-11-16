

**Conceitos iniciais sobre microsserviços e monolitos**

microsserviços - são uma abordagem arquitetônica e organizacional do desenvolvimento de software na qual o software consiste em pequenos serviços independentes que se comunicam usando APIs bem definidas. Esses serviços pertencem a pequenas equipes autossuficientes.

monolitos = serviços complexos, grandes, único.

![image-20210831212246070](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210831212246070.png)

**Pensando em escalabilidade vertical x horizontal**

Marthin  Fouler -*O termo "Arquitetura de microsserviço" surgiu nos últimos anos para descrever uma maneira particular de projetar aplicativos de software como conjuntos de serviços implantáveis independentemente. Embora não haja uma definição precisa desse estilo arquitetônico, existem certas características comuns em torno da organização em torno da capacidade de negócios, implantação automatizada, inteligência nos terminais e controle descentralizado de linguagens e dados.*

![image-20210914114116988](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914114116988.png)



**Visão geral sobre o Manifesto Ágil e ciclos de desenvolvimento**

![image-20210914115007459](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914115007459.png)

**Ecossistema de microsserviços**

![image-20210914115107400](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914115107400.png)

Esses conceitos chamamos de DOMINIO(negócio), escalabilidade e tem segregação de contexto.

**um não precisa do outro para funcionar**



**O que é uma API Pública e como se interagem**

![image-20210914115351668](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914115351668.png)

![image-20210914120221942](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914120221942.png)

![image-20210914120301088](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914120301088.png)

![image-20210914145246090](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914145246090.png)

![image-20210914150948117](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914150948117.png)

Como dividir um monolito em microsserviços

![image-20210914151322698](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914151322698.png)

a imagem acima exemplifica o contexto delimitado.

Modelo de integridade![image-20210914151924742](C:\Users\WINDOWS\AppData\Roaming\Typora\typora-user-images\image-20210914151924742.png)

tarefas síncronas - geralmente são tarefas normalmente de leitura de informação, elas tem que ser trabalhadas de uma maneira mais independente.

 o que ganha adotando Micro-serviços no projeto :

- resiliência
- escalabilidade
- desempenho





