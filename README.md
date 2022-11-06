# java101

public class Javanotortalaması {

    public static void main(String[] args) {
        
      Scanner input= new Scanner(System.in);

      int mat,fizik,turkce,muzik,tarih,ort;
      
      System.out.print("mat notunu girin:");
      mat=input.nextInt();
      
      System.out.print("fizik notunu girin:");
      fizik=input.nextInt();
      
      System.out.print("turkce notunu girin:");
      turkce=input.nextInt();
      
      System.out.print("muzik notunu girin:");
      muzik=input.nextInt();
      
      System.out.print("tarih notunu girin:");
      tarih=input.nextInt();
      
      ort=(mat+fizik+turkce+muzik+tarih)/5;
      
      System.out.println("ortalamanız:" + ort);
      
      String kaldigecti=(ort>=60)? "geçti":"kaldı";
      System.out.println(kaldigecti);
      
