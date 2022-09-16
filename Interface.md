## Definição
  ### Representação de interface na UML
   ![image](https://user-images.githubusercontent.com/104461441/190543857-c8c4a799-0a00-485d-92e0-7bf0280a7d14.png)

## Criação de uma classe que implementa uma interface
      public interface FiguraGeometrica
    {
     public String getNomeFigura();
     public int getArea();
     public int getPerimetro();
    }

## Sobreescrita de métodos
   Sintaxe:
  public class nome_classe implements nome_interface
   Onde:
  nome_classe – Nome da classe a ser implementada.
  nome_Interface – Nome da interface a se implementada pela classe.
  
## Polimorfismo
  ### Conversão de tipos

    {
        public static void main(String[] args)
        {
            double d = 100.04; 

            //explicit type casting
            long l = (long)d;

            //explicit type casting 
            int i = (int)l; 
            System.out.println("Double value "+d);

            //fractional part lost
            System.out.println("Long value "+l); 

            //fractional part lost
            System.out.println("Int value "+i); 
        } 
    }
