# Desafio4

#Questao4
package nadadores;

import java.util.Scanner;

/**
 *Categoria por Idade: Dado a idade de um nadador, classifique-o em
uma das seguintes categorias:
Infantil A: 5-7 anos
Infantil B: 8-10 anos
Juvenil A: 11-13 anos
Juvenil B: 14-17 anos
Adulto: maiores de 18 anos
 * @author Henrique
 * 
```java
public class Nadadores {

    public static void main(String[] args) {
        
        int idade;
        Scanner ler = new Scanner(System.in);
        
        System.out.println("Qual sua idade?");
        idade = ler.nextInt();
        
        if(idade>=5 && idade<=7){
            System.out.println("Infantil A");
        }else if(idade>=8 && idade<=10){
            System.out.println("Infantil B");
        }else if(idade>=11 && idade<=13){
            System.out.println("Juvenil A");
        }else if(idade>=14 && idade<=17){
            System.out.println("Juvenil B");
        }else if(idade>=18){
            System.out.println("Adulto");
        }else{
            System.out.println("idade invalida");
        }
    }
    
}
```
