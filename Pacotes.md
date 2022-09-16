## Definição
  ### Representação de pacotes na UML
  ![image](https://user-images.githubusercontent.com/104461441/190541210-034b949d-5a88-4129-80a6-4912850db490.png)

## Definição de um pacote em uma classe
  Um pacote no Java é um conjunto de classes localizadas na mesma estrutura hierárquica de diretórios.

## Importando uma classe de um pacote diferente
  É impossível importar classes para outro pacote, só é possível importar classes de um pacote para uma classe.

## Visibilidade de classes, atributos e métodos
  ### Default/Pacote
   A classe e seus membros só são acessíveis por classes do mesmo pacote, e o modificado é identificado pelo compilador.
  
      public class Modificador_Default {

      public static void main(String[] args) {

        String nome = “Flávia Bernandes”;
        System.out.printf(“Nome.: %s”,nome);
      }
    }

## Pacote default
  ### Importar uma classe em um pacote default
   É impossível importar classes para outro pacote, só é possível importar classes de um pacote para uma classe.
