## Definição
  ### Representação de herança na UML
   ![image](https://user-images.githubusercontent.com/104461441/190545885-b40fd026-755a-42da-b21e-4d69c55be1ab.png)

## Criação de uma classe que realiza herança
  A herança é um princípio de POO que permite a criação de novas classes a partir de outras previamente criadas. 
  Essas novas classes são chamadas de subclasses, ou classes derivadas; e as classes já existentes, que deram origem às subclasses,  
  são chamadas de superclasses, ou classes base.

## Sobreescrita de métodos
  Com a sobrescrita, da para especializar os métodos herdados das superclasses, alterando o seu comportamento nas subclasses por um mais específico. 

## Polimorfismo
  ### Conversão de tipos


## Visibilidade de atributos e métodos
  ### Protegido
   Um atributo e método protegido de uma classe só pode ser acessado e manipulado por objetos de classes permitida.

## Palavra reservada super
  ### Encadeamento de construtor
  
        // Java program to illustrate Constructor Chaining
      // within same class Using this() keyword
      class Temp
      {
          // default constructor 1
          // default constructor will call another constructor
          // using this keyword from same class
          Temp()
          {
              // calls constructor 2
              this(5);
              System.out.println("The Default constructor");
          }

          // parameterized constructor 2
          Temp(int x)
          {
              // calls constructor 3
              this(5, 15);
              System.out.println(x);
          }

          // parameterized constructor 3
          Temp(int x, int y)
          {
              System.out.println(x * y);
          }

          public static void main(String args[])
          {
              // invokes default constructor first
              new Temp();
          }
      }
  
  ### Encadeamento de método
   O encadeamento de métodos é a prática de chamar métodos diferentes em uma única linha, em vez de chamar métodos diferentes
   com a mesma referência de objeto separadamente. Sob este procedimento, temos que escrever a referência do objeto uma vez e
   então chamar os métodos separando-os com um (ponto.).
