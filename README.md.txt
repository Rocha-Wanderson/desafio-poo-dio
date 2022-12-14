Desafio: Aprenda na Pr?tica Programa??o Orientada a Objetos
?? SLIDES APRESENTADO NO PROJETO ??

Sejam bem-vindos ao desafio: APRENDENDO NA PR?TICA O PARADIGMA DE ORIENTA??O A OBJETOS.
Desafio este que tive a honra de co-criar com a plataforma de cursos online DIGITAL INNOVATION ONE ???? e disponibilizado de forma gratuita para a comunidade dos desenvolvedores Java.
?? O objetivo principal ? colocar em pr?tica umas das principais ferramentas da OO: ABSTRA??O, ENCAPSULAMENTO, HERAN?A E POLIMORFISMO, atrav?s de um projeto Java.

?? Pr?-Requisitos
? Conhecer a sintaxe da Java
? Java JDK 11
? IDE para desenvolvimento Java (usarei IntelliJ)
? Git
? Conta no GitHub
?? Passo-a-Passo
1. Vamos ABSTRAIR o DOM?NIO Bootcamp e MODELAR seus ATRIBUTOS E M?TODOS
2. Criaremos as CLASSES: Bootcamp, Cursos, Mentorias e Devs e vamos relaciona-las
3. As CLASSES Curso, Mentoria e Devs tamb?m ser?o MODELADOS, ou seja, criaremos seus ATRIBUTOS E M?TODOS
4. Para que o c?digo fique mais leg?vel e de f?cil manuten??o, iremos utilizar de algumas das ferramentas que o PARADIGMA DE ORIENTA??O A OBJETOS (POO) nos oferece: ABSTRA??O, ENCAPSULAMENTO, HERAN?A E POLIMORFISMO
5. E para representar CLASSES que foram criadas e relacionadas, iremos transforma-las em OBJETOS
?? Paradigma de Programa??o Orientado a Objetos (POO)
A vis?o de Orienta??o a Objetos (OO) ? aquela de um mundo de objetos que interagem.
Este paradigma ? um modelo de an?lise, projeto e programa??o baseado na aproxima??o entre o mundo real e o mundo virtual, atrav?s da cria??o e intera??o entre classes, atributos, m?todos, objetos, entre outros.
S?o 4 os pilares principais do POO: ABSTRA??O, ENCAPSULAMENTO, HERAN?A E POLIMORFISMO.

?? ABSTRA??O:
Habilidade de concentrar-se nos aspectos essenciais de um dom?nio, ignorando caracter?sticas menos importantes ou acidentais. Nesse contexto, objetos s?o abstra??es de entidades existentes no dom?nio em quest?o.

?? ENCAPSULAMENTO:
Encapsular significa esconder a implementa??o dos objetos. O encapsulamento favorece principalmente dois aspectos de um sistema: a manuten??o e a evolu??o.

?? HERAN?A:
Permite que voc? defina uma classe filha que reutiliza (herda), estende ou modifica o comportamento de uma classe pai. A classe cujos membros s?o herdados ? chamada de classe base. A classe que herda os membros da classe base ? chamada de classe derivada.

?? POLIMORFISMO:
Capacidade de um objeto poder ser referenciado de v?rias formas. Cuidado, polimorfismo n?o quer dizer que o objeto fica se transformando, muito pelo contr?rio, um objeto nasce de um tipo e morre daquele tipo, o que pode mudar ? a maneira como nos referimos a ele. A capacidade de tratar objetos criados a partir das classes espec?ficas como objetos de uma classe gen?rica ? chamada de polimorfismo.


?? CONCEITOS FUNDAMENTAIS POO ??
?? DOM?NIO:
Dom?nio da aplica??o, tamb?m conhecida como camada de neg?cio ou de objetos de neg?cio, ? aquela onde est?o localizadas as classes que fazem parte do dom?nio do problema, ou seja, classes correspondentes a objetos que fazem parte da descri??o do problema.
?? CLASSE:
Um elemento do c?digo que tem a fun??o de representar objetos do mundo real. Dentro dela ? comum declararmos atributos e m?todos, que representam, respectivamente, as caracter?sticas e comportamentos desse objeto.
?? ATRIBUTO:
Atributos s?o, basicamente, a estrutura de dados que vai representar a classe. Os atributos tamb?m s?o conhecidos como VARI?VEL DE CLASSE, e podem ser divididos em dois tipos b?sicos: atributos de inst?ncia e de classe.
?? VARI?VEL:
Uma ?regi?o de mem?ria (do computador) previamente identificada cuja finalidade ? armazenar os dados ou informa??es de um programa por um determinado espa?o de tempo?.
?? M?TODO:
Os m?todos representam os estados e a??es dos objetos e classes.
?? OBJETO:
Em POO, objeto ? um "molde" de uma determinada classe, que passa a existir a partir de uma inst?ncia da classe. A classe define o comportamento do objeto, usando atributos (propriedades) e m?todos (a??es). Objeto em ci?ncia da computa??o, ? uma refer?ncia a um local da mem?ria que possui um valor. Um objeto pode ser uma vari?vel, fun??o, ou estrutura de dados.
?? INST?NCIA:
Uma inst?ncia de uma classe ? um novo objeto criado dessa classe, com o operador new. Instanciar uma classe ? criar um novo objeto do mesmo tipo dessa classe. Uma classe somente poder? ser utilizada ap?s ser instanciada.

?? Linguagem de Programa??o vs Paradigma de Linguagem de Programa??o
? LINGUAGEM DE PROGRAMA??O:
? uma linguagem formal que, atrav?s de uma s?rie de instru??es, permite que um programador escreva um conjunto de ordens, a??es consecutivas, dados e algoritmos para criar programas que controlam o comportamento f?sico e l?gico de uma m?quina.
Seguem alguns exemplos de como as linguagens de programa??o podem ser classificadas:

?? N?vel de abstra??o:
Baixo N?vel: Assembly
M?dio N?vel: C, C++, D, Objective C, etc.
Alto N?vel: Java, C#, PHP, Javascript, etc.
Alt?ssimo N?vel: Python, Ruby, Elixir, etc.

?? Paradigma de programa??o:
Programa??o Estruturada: C, Pascal, Ada, etc.
Programa??o Orientada a Objetos: Java, C#, C++, Objective C, D, etc.
Programa??o Funcional: Lisp, Scheme, Erlang, Elixir, etc.

?? Linguagens classificadas pela arquitetura da aplica??o:
Desktop: C, C++, Object Pascal, Java, etc.
Web: PHP, Ruby, Javascript, Java, etc.

?? Tipo de execu??o:
Linguagens compiladas: C, C++, Pascal, D, GO, etc.
Linguagens Interpretadas: Python, Ruby, PHP, Javascript, etc.
Linguagens Hibridas: Java, Erlang, Elixir, etc.
? PARADIGMA DE LINGUAGEM DE PROGRAMA??O
? um conjunto de caracter?sticas que podem ser utilizados para categorizar determinado grupo de linguagens. Um paradigma pode oferecer t?cnicas apropriadas para uma aplica??o espec?fica.

PARADIGMAS PRINCIPAIS e SEUS SUBPARADIGMAS

?? 1. Paradigma Imperativo
Neste paradigma, o programa descreve o processamento necess?rio para solucionar o problema. Assim, o paradigma imperativo ? caracterizado por execu??o sequencial de instru??es, pelo uso de vari?veis que representam posi??es de mem?ria e pelo uso de instru??es de atribui??o que alteram os valores dessas vari?veis.
Vejamos alguns Subparadigmas do Paradigma Imperativo e exemplos linguagens de programa??o que adotam esses subparadigmas.

?? 1.1 Paradigma estruturado: ALGOL 58 e ALGOL 60
?? 1.2 Paradigma concorrente: Java e Ada
?? 1.3 Paradigma Orientado a Objetos: Smalltalk e Java

?? 2. Paradigma Declarativo
Este paradigma ? o modelo no qual os resultados s?o descritos, mas os passos para chegar aos resultados n?o s?o estabelecidos.
Vejamos alguns Subparadigmas do Paradigma Declarativo e exemplos linguagens de programa??o que adotam esses subparadigmas:

?? 2.1 Paradigma Funcional: Lisp e Haskell
?? 2.2 Paradigma L?gico: Prolog

?? Contribuindo
Este reposit?rio foi criado para fins de estudo, ent?o contribua com ele.
Se te ajudei de alguma forma, ficarei feliz em saber. E caso voc? conhe?a algu?m que se identidique com o conte?do, n?o deixe de compatilhar.

Se poss?vel:
?? Star o projeto
?? Encontrar e relatar issues
Disponibilizado com ? por cami-la.