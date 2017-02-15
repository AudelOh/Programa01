# Programa01
Programa Java que lea dos números enteros por teclado y los muestre por pantalla.
package numero;

import java.util.Scanner;




/**
 *
 * @author AudiGS
 */
public class Numero {
    

    public static void main(String[] args) {
        int n1,n2;
      Scanner sc = new Scanner(System.in);
        System.out.println("Introduce un numero entero: ")
        n1= sc.nextInt();
           System.out.println("Introduce otro numero entero: ")
        n2= sc.nextInt();
        System.out.println("Los numumeros que escribio son: "+ n1 +" y" +n2);
        
    }
    
}
