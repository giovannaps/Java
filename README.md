public class Main {

   public static void numerosDe1a100() {
    for (int i = 1; i < 101; i++) {
    System.out.print(i);
      
      if (i < 100)
        System.out.print(",");
        
    }
  }
  public static void numerosImpares() {
    int numeroInicial = 11;
    int numeroFinal = 999;
    int razao = 2;
    int numeroDeTermos = (numeroFinal - numeroInicial) /razao + 1;
    int soma = numeroDeTermos/razao * (numeroInicial + numeroFinal);

     System.out.print(soma);
    


  }
  public static void multiplosDe3() {
   
 for (int i = 1; i < 1000; i++) {
  Boolean numeroProibido = i % 10 == 3; 
    if (i % 3 == 0 && !numeroProibido){
      System.out.print(i);  
     System.out.print(",");
    }

   
 }
 }
 

   
    

    
    public static void main(String[] args){
    System.out.println("Lista dos números de 1 a 100: ");
    numerosDe1a100();
      
      System.out.println();
      
    System.out.println("Soma de todos os números ímpares entre 10 e 1000: ");
       numerosImpares();
      
       System.out.println();
      
       System.out.println("Todos os múltiplos de 3 que NÃO terminam em 3 entre 1 e x: ");
      multiplosDe3();
      
      
  }
}
