## Definição
 ### Representação de classe e objeto na UML
   ![image](https://user-images.githubusercontent.com/104461441/190533113-c956ce67-e1a7-4827-8975-fd0eeb7f069f.png)

 ### Diferença entre classe e objeto
 
   Classe é o modelo a ser seguido para que o objeto seja construído dentro de certas características. É algo lógico.
   O objeto é algo concreto. Nele os elementos estão de fato presentes ali.Objeto possui valores para os estados definidos 
   e chamam os comportamentos definidos executando os algoritmos.
   
## Atributos
  O atributis são as características que definem a classe.
  Os atributos de uma classe Java pode ser representados por variáveis com o prefixo public.
  
  public class SerHumano {
    
    // Atributos da classe ser humano
    public String nome;
    public int idade;
    public String CorDosOlhos;
    public String CorDosCabelos;
    
## Métodos
  Os métodos são as ações da classe, diz o que a classe vai fazer.
  Em Java são criados com a sintaxe public void NomeDoMetodo() {} e dentro do par de chaves é colocado 
  o código do método. 

## Construtor
      modificadores de acesso (public nesse caso) + nome da classe (Carro nesse caso) + parâmetros (nenhum definido
    neste caso). O construtor pode ter níveis como: public, private ou protected.
    
## Objeto
  Os objetos são características definidas pelas classes. 
  
## Inicialização de um objeto
  Inicializar um objeto significa armazenar dados no objeto. 
  
       class Aluno {  
      int id;  
      String nome;  
     }  
     class TesteAluno2 {  
      public static void  main(String args []) {  
       Aluno a1 = new Aluno();  
       a1.id = 101 ;  
       a1.nome = "Sonoo" ;  
       System.out.println(a1.id + "" + s1.nome); // imprimindo membros com um espaço em branco   
      }  
     }  

## Utilização de um objeto
  
## Comparação de objetos
   A comparacão de objetos é feito através dos métodos hashCode() e equals(), da classe Object.

       public class Livro {

     private String nome; 
     private String autor;
     private double preco;

     public Livro(String nome, String autor, double preco) {
          this.nome = nome; 
          this.autor = autor; 
          this.preco = preco;
     }

     }

     List<Livro> meusLivros = todosOsLivros();

     System.out.println(meusLivros);

## Método toString
  
      public String toString() {
     return getClass().getName() + "@"
                  + Integer.toHexString(hashCode());
    }
    
## Visibilidade de atributos e métodos
 ### Público
   Um atributo público de uma classe pode ser diretamente acessado e manipulado por objetos de outras classes.
      
 ### Privado
   Um atributo privado de uma classe não pode ser diretamente acessado e manipulado por objetos de outras classes.
   
## Sobrecarga de métodos

