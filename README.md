# Ejercicio1_actividad1_poo.java
Ejercicio1_actividad1_poo

package edadmama;
import java.util.Scanner;

public class Edadmama {
    
    public static void main(String[] args) {
        // TODO code application logic here
        int EDJUAN,EDALBER,EDANA,EDMAMA;
        System.out.println("Ingrese la edad de Juan:  ");
        Scanner entrada = new Scanner (System.in);
        EDJUAN = entrada.nextInt();
        EDALBER= 2*EDJUAN/3;
        EDANA= 4*EDJUAN/3;
        EDMAMA= EDJUAN+EDALBER+EDANA;
        System.out.println("la edad de Alberto es: " +EDALBER );
        System.out.println("la edad de Juan es: " +EDJUAN );
        System.out.println("la edad de Ana es: " +EDANA );
        System.out.println("la edad de Mama es: " +EDMAMA );
        
        
    }
    
}
