## Definição
  ### Representação de classe abstrata na UML
   ![image](https://user-images.githubusercontent.com/104461441/190545102-f5f2b499-75d1-471d-9a82-e9941f1bd78b.png)
  
## Criação de uma classe que extende uma classe abstrata
   Para ter um objeto de uma classe abstrata é necessário criar uma classe mais especializada herdando dela e então instanciar essa nova classe. 
  Os métodos da classe abstrata devem então serem sobrescritos nas classes filhas.
  
      abstract class Conta {

      private double saldo;

      public void setSaldo(double saldo) {
        this.saldo = saldo;
      }

      public double getSaldo() {
        return saldo;
      }

      public abstract void imprimeExtrato();

    }

## Polimorfismo
  ### Conversão de tipos
   O polimorfismo permite que classes abstratas consigam receber comportamentos através de classes concretas.
