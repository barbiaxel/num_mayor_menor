# num_mayor_menor
Pide 3 números y nos dice cual es el mayor y el menor.
package ejercicio1;
//pide 3 numeros y nos dice cual es el mayor y el menor.
import java.util.Scanner;

public class ejercicio1 {

	public static void main(String[] args) {
		int a=0,b=0,c=0;
		Scanner teclado = new Scanner(System.in);
		
		System.out.println("Introduce el primer número:");
		a=teclado.nextInt();
		System.out.println("Introduce el segundo número:");
		b=teclado.nextInt();
		System.out.println("Introduce el tercer número:");
		c=teclado.nextInt();
		
		if (a >= b && a >= c) 
			System.out.println("El número mayor es el: "+a);
		else if (b > a && b >= c)
			System.out.println("El número mayor es el: "+b);
		else 
			System.out.println("El número mayor es el: "+c);
		
		if (a <= b && a <= c)
			System.out.println("El número menor es el: "+a);
		else if (b < a && b <= c)
			System.out.println("El número menor es el: "+b);
		else 
			System.out.println("El número menor es el: "+c);
		
			}
		}
			

