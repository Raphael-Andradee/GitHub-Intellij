import java.util.Scanner;
import java.util.Locale;
public class Main {
    public static void main(String[] args) {
  Locale.setDefault(Locale.UK);
  Scanner sc = new Scanner(System.in);

 int numeros;

 System.out.println("Indique um numero: ");
 numeros = sc.nextInt();

 if(numeros<0){
     System.out.println("NEGATIVO");
 }
 else{
     System.out.println("POSITIVO");
 }


   sc.close();
    }
}