# NAIR-RUSSEL-DE-LA-CRUZ-CHATE

import java.util.Scanner;

public class ContadorProgresivo {
    public static void main(String[] args) {
        // 1. Declaración del contador (acumulador/contador progresivo)
        int contador = 1;
        int limite;
        
        // 2. Entrada de datos
        Scanner entrada = new Scanner(System.in);
        System.out.print("Ingrese el número límite para contar: ");
        limite = entrada.nextInt();

        // 3. Estructura de control: do-while
        do {
            // Mostramos el valor actual del contador
            System.out.println("Valor actual: " + contador);
            
            // Incremento progresivo (aquí aumentamos el contador)
            contador = contador + 1; 
            
        } while (contador <= limite); // Condición de repetición

        // 4. Mensaje final
        System.out.println("Conteo finalizado.");
        entrada.close();
    }
}
